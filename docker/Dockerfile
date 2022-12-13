FROM ubuntu:22.04
RUN apt-get update && apt-get upgrade -y

# Get the packages required to run pandoc_resume
ENV TERM=xterm-256color
RUN apt-get install -y git make pandoc context

# Add Samba, Netatalk, supervisord, and SSH so that we can see the files that we created
RUN apt-get install -y samba netatalk supervisor openssh-server sudo autossh

# Set up SSH
RUN ssh-keygen -A;\
  mkdir -p /var/run/sshd

# Copy config files for supervisord defaults, samba, afp (netatalk), and ssh into supervisord
COPY supervisord.conf /etc/supervisor/conf.d/
COPY samba.conf /etc/supervisor/conf.d/
COPY netatalk.conf /etc/supervisor/conf.d/
COPY ssh.conf /etc/supervisor/conf.d/
COPY smb.conf /etc/samba/
COPY afp.conf /etc/netatalk/

RUN adduser --disabled-password --gecos "" resume
RUN echo "resume:resume" | chpasswd
RUN (echo "resume"; echo "resume") | smbpasswd -a resume
RUN echo "resume ALL=(ALL) NOPASSWD:ALL" >/etc/sudoers.d/resume;\
 chmod 440 /etc/sudoers.d/resume

# Grab the repo so we can make a resume
WORKDIR /resume
RUN cd /home/resume; \
 mkdir pandoc_resume; \
 cd pandoc_resume; \
 git init .; \
 git remote add origin git@github.com:toddbu/pandoc_resume.git; \
 cd ..; \
 chown -R resume.resume *;

# exposes samba's default ports (445 for smbd, afp port 548)
EXPOSE 445 548

ENTRYPOINT ["supervisord", "-c", "/etc/supervisor/supervisord.conf"]
