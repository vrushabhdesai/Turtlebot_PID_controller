# Turtlebot Path Tracking Using PID Controller

The goal of the project was to designed point-to-point and multi-point PID controller for turtlebot. To start with we simulated the PID algorithm performance on turtlebot3 using ROS gazeboo. PID controller tuning was done using itterative method. Once optimal gain values were obtained we deployed PID controller on actual turtlebot hardware and compared simulation results with actual hardware performance.
Following shows hardware implementation:

![sample_results](images/controls_gif1.gif)
![sample_results](images/controls_gif2.gif)

Simulation results on ROS can be seen in following video

[`Results Video`] 

[`Results Video`]: https://www.youtube.com/watch?v=8Y3Wkv1REyE&feature=youtu.be

## Execution

To run this repository on your local machine follow this instructions:

```
1. cd catkin_ws/src
```
```
2. git clone this repo
```
```
3. cd ..
```
```
4. catkin_make
```
```
5. roslaunch turtlebot3_gazebo turtlebot3_empty_world.launch
```
```
6. rosrun pid_control pid_control 
```



