# Running containers

To run the go server on [http://localhost:8153](http://localhost:8153), simply execute:

    docker run -d --name go-server -p 8153:80 patforna/go-server

# Building image from scratch

The following commands build the images from scratch and tag it accordingly (replace 14.1.0 with new version).

    docker build -t patforna/go-server:14.1.0 go-server && \
    docker tag patforna/go-server:14.1.0 patforna/go-server:latest