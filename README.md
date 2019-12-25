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

![gui](https://i.imgur.com/ebk8hyn.jpg)
