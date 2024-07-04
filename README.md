# ROS_Download
Many people face problems when downloading ROS noetic or foxy, so I will explain how to download them.
*Note*: You should download Ubuntu first.
## Downloading ROS noetic:
Go to this [LINK](http://wiki.ros.org/ROS/Installation)
Click on ROS Noetic Ninjemys
![Screenshot (101)](https://github.com/Mapoto99/ROS_Download/assets/174211031/7e78f198-3365-498e-9540-d5eb6542b8f8)
Click on Ubuntu
![Screenshot (102)](https://github.com/Mapoto99/ROS_Download/assets/174211031/bcbc3d6b-4906-460e-b0ae-48d0089cee1d)
Open the terminal on Ubuntu, then type the following respectively:
1-
```
sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'
```
2-
```
sudo apt install curl # if you haven't already installed curl
curl -s https://raw.githubusercontent.com/ros/rosdistro/master/ros.asc | sudo apt-key add -
```
3-
```
sudo apt update
```
4-
```
sudo apt install ros-noetic-desktop-full
```
5-
```
echo "source /opt/ros/noetic/setup.bash" >> ~/.bashrc
source ~/.bashrc
```
