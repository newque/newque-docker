Newque-Docker
###########
[![Build Status](https://travis-ci.org/newque/newque-docker.svg?branch=master)](https://travis-ci.org/newque/newque-docker)

# Build the image
docker build -t newque .

# Run the image and drop in to a bash prompt
docker run -it newque bash

# Run the image and map ports to host
docker run -p 8000:8000 -p 8001:8001 -p 8005:8005 newque
