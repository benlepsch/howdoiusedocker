# how do i use docker? 
seriously guys this is not a joke can someone explain how i deploy a website using a docker container

## what i'm doing
 - building images with `docker build -t <name of image> .` and run them with `docker run <name of image>`

## errors this has:
 - i'm trying to deploy it on port 80, flask says on startup that it's running on "0.0.0.0:5000"
 - when i go to my computer's ip address on port 5000, it loads infinitely. when i use port 80, i get a blank website
