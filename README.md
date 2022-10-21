# Robotic-Nano-Degree-Project-2

## Description

This is the second project of the Robotics udacity nano-degrees. 

## Prerequistes

- Udacity Robond virtual machine running on VMWare Player

## Building

```shell
# Create the workspace
mkdir -p ~/catkin_ws/src
cd  ~/catkin_ws/src
# Clonning the Repo
git clone git@github.com:RemonComputer/Robotic-Nano-Degree-Project-2.git 
cd ..
# Compiling the packages
catkin_make
```

## Running

- Open the first terminal to launch the robot package
```shell
roslaunch my_robot world.launch
```

- Open another terminal to run the ball_chaser
```shell
roslaunch ball_chaser ball_chaser.launch
```

- You can view the image topic using Rviz.

- Put the ball infront of the robot.

## What to expect

- The Robot will chase the white ball.

## Screenshots

![Robot chassing the ball](imgs/robot_chassing_ball.jpg)
