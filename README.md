# Ansible Server Base

This repo contains all packages I want, when I have to set up a new linux
server or virtual machine. 

On the new machine I create a user `schaary`, who's getting sudo and docker
grants and several packages:

- zsh
- htop
- nvim
- tmux
- mc 
- whois
- docker
- docker-compose

Everything happens in the file `provision.yml`. To use this repo, start with
the script `ansible-bash.sh` - copy it to the server and run it from cli.
