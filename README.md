# docker-ros-gazebo-vnc
This repository is developing ros-vnc environment. And then it can use rviz and gazebo on vnc.

# docker-ubuntu-vnc-desktop

Docker image to provide HTML5 VNC interface to access Ubuntu 18.04 LXDE desktop environment.

This image can use rviz and gazebo on VNC.

# Quick Start
Run the docker image and open `port 6080`

```
docker run -it --rm -p 6080:80 mtakeshi1222/ros_gui
```
http://127.0.0.1:6080/

![gui](https://i.imgur.com/ebk8hyn.jpg)

I was based on [ct2034/docker-ubuntu-vnc-desktop](https://github.com/ct2034/docker-ubuntu-vnc-desktop) and [dorowu/ubuntu-desktop-lxde-vnc](https://hub.docker.com/r/dorowu/ubuntu-desktop-lxde-vnc) to create the this image.

Then, I couldn't write a Dockerfile because that couldn't install ros melodic.

I hope pull requests and comment to my Dockerfile or image.
