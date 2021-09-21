# Laboratory 2_ecse373_f21_yxs1090_navvis_description
ROS use URDF and XACRO, which are XML based file type, to describe and create and automate the description of robots. We can use the package `launch files` to view the robot description in `rviz` with and without the joint_state_publisher `GUI`,
## dependence
ROS Melodic

the joint_state_publisher_GUI

rviz

velodyne description
## `rviz` with the joint_state_publisher `GUI`
### URDF
```
roslaunch navvis_description launch_display.launch
```
### XACRO
```
roslaunch navvis_description launch_display.launch use_xacro:=true
```

## `rviz` without the joint_state_publisher `GUI`
### URDF
```
roslaunch navvis_description launch_display.launch  use_gui:=false
```
### XACRO
```
roslaunch navvis_description launch_display.launch use_xacro:=true  use_gui:=false
```
