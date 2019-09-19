# Intro to Chrome Exploitation
## Abstract
Over 3 billion browser devices are actively loading arbitrary data served by someone else. What happens if one of those pages contains maliciously crafted JavaScript? Could they capture your passwords, perform UXSS, or worse - execute local code on your machine? In this session, you will get the opportunity to explore the anatomy and play with common vulnerability patterns in the renderer process of Chrome. This will be an interactive class; please bring a laptop with Docker installed.

## Slides
Will be uploaded before class.

## Docker Environment
To follow along with the class, you will need to create a container from the prebuilt docker image.
1. Login to Docker with the creds provided in class.
1. Build the container: `./build`. Alternatively, you can `docker pull owasp2019chrome/class-env:latest`.

### Managemnt
- `start` - Start the built image
- `stop`  - Stop the running image
- `connect [COMMAND]` - Connect to the running container. By default, if no second argument is provided, a new `tmux` session is created.
