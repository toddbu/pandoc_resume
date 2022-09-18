## The Markdown Resume

### Running the Docker Container

```
git clone https://github.com/toddbu/pandoc_resume
cd pandoc_resume/docker
./build
./start
docker exec -it resume bash
  # build a tunnel back to the Mac
  autossh -M 0 -o "ServerAliveInterval 30" -o "ServerAliveCountMax 3" -R 2548:localhost:548 toddbu@10.0.0.20
  sudo apt-get install inotify-hookable
  inotify-hookable -w markdown -c "make"
```

You can connect to the `resume` share by typing Cmd+K in the Finder app on your Mac and mounting `afp://localhost:2549/resume` using the username/password combination of `resume`/`resume`

### Manual Instructions:

On Ubuntu 22.04 LTS, do the following...

```
sudo apt-get update
sudo apt-get install -y pandoc context
git clone https://github.com/toddbu/pandoc_resume
cd pandoc_resume
vi resume.md
make
```

Requirements:

 * ConTeXt
 * pandoc
