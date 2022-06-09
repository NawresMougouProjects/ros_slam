# ros_slam
## mapping and navigation of the turtlebot3
#### 1- open roscore on the terminal.
#### 2-
```
$ roslaunch turtlebot3_bringup turtlebot3_robot.launch
```
#### 3-
```
$ export TURTLEBOT3_MODEL=burger
```
####   
```
$ roslaunch turtlebot3_slam turtlebot3_slam.launch
```
#### 4- save the map with the following command : 
```
$ rosrun map_server map_saver -f ~/map
```
#### 5- 
```
$  roslaunch turtlebot3_navigation turtlebot3_navigation.launch map_file:=$HOME/map.yaml
```
#### 6- pose estimation using the teleop command with 
```
$ roslaunch turtlebot3_teleop turtlebot3_teleop_key.launch
```
#### 7- navigation with 2D NAV GOAL.
# Result



https://user-images.githubusercontent.com/62567205/172961465-e1a167fe-d657-4c31-965b-ca5724378902.mp4

