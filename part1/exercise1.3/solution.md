Secret message: 'You can find the source code here: https://github.com/docker-hy'

Commands given:

    docker run -d --name ex1_3 devopsdockeruh/simple-web-service:ubuntu
    docker exec -it ex1_3 bash

then, within the container:

    tail -f ./text.log
