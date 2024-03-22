#### Create a Docker image with Nginx based Webserver

##### Download the image

    docker pull ruyoliv/pr:nginx

##### Run the container

    docker run -it --rm -p 8080:80 --name mywebserver ruyoliv/pr:nginx

##### Check it out - in the browser

    localhost:8080
