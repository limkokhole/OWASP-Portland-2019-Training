# Intro to Chrome Exploitation
## Overview
Slides and solutions for exploitation exersices are located in the `./src` directory.

## Docker Environment
To follow along with the class, you will need to create a container from the prebuilt docker image. The image is 8GB and **expands to 20GB.**
1. Install Docker:  
  macOS: `brew cask install docker && brew install docker`  
  Ubuntu: `sudo apt update && sudo apt install docker.io`  
  Windows: https://docs.docker.com/docker-for-windows/install/
1. Pull: `./pull` -- This will pull `owasp2019chrome/class-env:latest` from docker hub.
    - Add any customizations to the Dockerfile

### Managemnt
- `start` - Start the built image
- `stop`  - Stop the running image
- `connect [COMMAND]` - Connect to the running container. By default, if no argument is provided, a new `tmux` session is created.

