# A part of Udacity Nanodegree
### Where Am I
Localization of a mobile robot using Adaptive Monte Carlo Localization Algorithm  in Mapped Environment. The Mobile Robot is equipped with RGB-D Camera and Hokuyo Lidar.

### Description
The project involves utilization of ROS AMCL package to accurately localize a mobile robot inside a map in the Gazebo simulation environments. 
pgm_map_creator ROS package is used to create a map of your Gazebo environment for the localization purpose.
Tele-Operation/Navigation Stack is used to drive the robot within the Gazebo environment.
Rviz is used for the visualization of the robot's perception modules.


### Basic Build Instructions
1. Create a catkin Workspace
```
    mkdir -p catkin_ws/src
    cd catkin_ws/src
    catkin_init_workspace
    cd ..
    catkin_make
```
2. Clone the repository
```
    cd catkin/src
    git clone https://github.com/Gopsee/WhereAmI.git
    cd ..
    catkin_make
```
3. Source the workspace
```
    source devel/setup.bash
``` 
4. Launch the main file
```
    roslaunch main main.launch
```
