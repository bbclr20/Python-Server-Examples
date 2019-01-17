# Docker

## Build dockerfile

    sudo docker build -t flask_app .

## Run container

Start the server

    sudo docker run -d -p 9090:9090 -p 9191:9191 flask_app

using bind mount **-v $(pwd)/app:/app** to link to the host folder
