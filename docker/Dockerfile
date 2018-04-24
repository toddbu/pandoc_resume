FROM ubuntu:16.04
RUN apt-get update; apt-get upgrade -y

# Get the packages required to run pandoc_resume
ENV TERM=xterm-256color
RUN apt-get install -y git make pandoc context

# Add Samba so that we can see the files that we created
RUN apt-get install -y samba
# RUN echo "1"
# RUN cat /etc/samba/smb.conf
# RUN echo "==="
RUN sed -i 's/;.*\[homes\]/\[homes\]/' /etc/samba/smb.conf;\
 sed -i 's/;.*comment = Home Directories/    comment = Home Directories/' /etc/samba/smb.conf;\
 sed -i 's/;.*read only = yes/    read only = no/' /etc/samba/smb.conf;\
 sed -i 's/;.*create mask = 0700/    create mask = 0700/' /etc/samba/smb.conf;\
 sed -i 's/;.*directory mask = 0700/    directory mask = 0700/' /etc/samba/smb.conf;\
 sed -i 's/;.*valid users = %S/    valid users = %S/' /etc/samba/smb.conf
RUN cat /etc/samba/smb.conf
RUN adduser --disabled-password --gecos "" resume
RUN echo "resume:resume" | chpasswd
RUN (echo "resume"; echo "resume") | smbpasswd -a resume
COPY boot /root/boot
RUN chmod 770 /root/boot
WORKDIR /root

# Grab the repo so we can make a resume
RUN cd /home/resume;\
 git clone https://github.com/toddbu/pandoc_resume.git;\
 chown -R resume.resume *
