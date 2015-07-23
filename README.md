# cloudstation-docker
docker run -d --name cloudstation -e DISPLAY=$DISPLAY -v /etc/machine-id:/etc/machine-id -v /tmp/.X11-unix:/tmp/.X11-unix -v $HOME:/data abgn/cloudstation
