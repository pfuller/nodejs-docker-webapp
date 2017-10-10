# To build
docker build -t <your username>/node-web-app .

# Check images was built
docker images

# run the image
docker build -t <your username>/node-web-app .

# Get container ID
$ docker ps

# Print app output
$ docker logs <container id>

# Example
Running on http://localhost:8080

# Enter the container
$ docker exec -it <container id> /bin/bash

# The container will be at http://localhost:49160/ and will return Hello world if working