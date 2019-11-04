# Docker images

Dockerfiles in subfolders of this folder can be used to build Docker images for use in development.

## static

Builds static version of the page. To build the image issue following command from the top of the repository:
`docker build -f docker/static/Dockerfile --tag modelrobot/static .`

To run a container based on the image:

`docker run -p 80 modelrobot/static`

The web page can be accessed as localhost:80
