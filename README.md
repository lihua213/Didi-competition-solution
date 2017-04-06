# DiDi competition 

[Here](https://www.udacity.com/didi-challenge) you can find more info about the challenge. 

[![GIF](./visualization.gif)](https://www.youtube.com/watch?v=8ajTBb6EDWE)

This repository is to provide visualization, calibration, detection ROS nodes.

## Instructions:

### Install ROS:
Follow instructions you find in this <a href="http://wiki.ros.org/ROS/Installation" target="_parent">page</a>.

### Download dataset:
* Download the 22GB dataset from [here](http://academictorrents.com/details/18d7f6be647eb6d581f5ff61819a11b9c21769c7).

### Setup:
`$ git clone https://github.com/omgteam/Didi-competition-solution.git`

`$ cd Didi-competition-solution`

`$ catkin_make`

`$ source devel/setup.bash`

### Visualization:
`$ roslaunch didi_visualize visualize_rviz.launch rosbag_file:=PATH/NAME.bag`

This module is borrowed from https://github.com/jokla/didi_challenge_ros.