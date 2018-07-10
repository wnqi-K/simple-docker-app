# simple-docker-app

This has been build as a Docker Image, simply "docker pull wenqiangk/docker_sample" can download this image to your machine. 

Then using "docker run -d -p PORT_YOU_LIKE:5000 wenqiangk/docker_sample" to run it.

Enter localhost:PORT_YOU_LIKE in your browser to view the page.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~`
OR, since the Dockerfile is ready, build your own docker image,

simply clone the repo,
"docker build -t YOUR_DOCKER_ID/YOUR_IMAGE_NAME .", remember "docker login" if this is your first time to build.
