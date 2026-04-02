# AMR-ros2-simulation-with-gz-fortress

Simulation of an AMR in different gz worlds using ros2 and nav2.

## Project overview

This ros2 pkg simulates a self made robot with different sensor plugins in different gz worlds. It can also navigate and map the environments as well as idetifying objects.

## System diagram

Work in progress !

## Prerequisites and dependencies

This project requires the following softwares:
 - Ubuntu 22.04
 - ROS 2 [Humble](https://docs.ros.org/en/humble/Installation/Ubuntu-Install-Debs.html)
 - Gazebo [Fortress](https://gazebosim.org/docs/latest/ros_installation/)

## Installation instructions

1. Clone the repo
```bash
git https://github.com/R3nat012/AMR-ros2-simulation-with-gz-fortress.git
```

2. Install dependencies
```bash
cd your_ws
rosdep install --from-paths src --ignore-src -r -y
```

3. Build the workspace
```bash
cd your_ws
colcon build
source install/setup.bash
```

## Project structure

Work in progress !

## Features and roadmap

Future updates and debugging:
 - Gazebo fortress world launch  [In progress]
 - Spawn robot [In progress]
 - Teleop [In progress]
 - SLAM [In progress]
 - Nav2 [In progress]

## References