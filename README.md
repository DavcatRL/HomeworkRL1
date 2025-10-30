# HomeworkRL1
This repository contains ROS packages that implement the visualisation and control of the ‘Armando’ robot in simulation, using Rviz and Gazebo.

Before running this code, ensure you have added the following lines to your Dockerfile and rebuilded your ros2 docker image:
<pre> ``` bash
RUN apt-get install -y ros-humble-ros-ign-bridge && \
apt-get install -y ros-humble-ros-gz && \
apt-get install ros-humble-controller-manager -y && \
apt-get install ros-humble-ros2-control -y && \
apt-get install ros-humble-ros2-controllers -y && \
apt-get install ros-humble-ign-ros2-control -y && \
apt-get install ros-humble-joint-state-publisher -y && \
apt-get install ros-humble-joint-state-publisher-gui -y && \
apt-get install ros-humble-xacro -y && \
apt-get install ros-humble-urdf-launch && \
apt-get install ros-humble-urdf-tutorial ```</pre>

