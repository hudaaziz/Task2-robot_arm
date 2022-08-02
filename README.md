# Task2-robot_arm
Installing the package arduino_robot_arm :
- Add the “arduino_robot_arm” package to “src” folder

$ cd ~/catkin_ws/src

$ sudo apt install git

$ git clone https://github.com/smart-methods/arduino_robot_arm

- Install all the dependencies

$ cd ~/catkin_ws

$ rosdep install --from-paths src --ignore-src -r -y

$ sudo apt-get install ros-melodic-moveit

$ sudo apt-get install ros-melodic-joint-state-publisher ros-melodic-joint-state-publisher-gui

$ sudo apt-get install ros-melodic-gazebo-ros-control joint-state-publisher

$ sudo apt-get install ros-melodic-ros-controllers ros-melodic-ros-control

Compile the package

$ catkin_make

$ cd ~/catkin_ws/src
 
$ git clone https://github.com/smart-methods/arduino_robot_arm.git 
 
$ cd ~/catkin_ws
 
$ rosdep install --from-paths src --ignore-src -r -y
 
$ sudo apt-get install ros-noetic-moveit
 
$ sudo apt-get install ros-noetic-joint-state-publisher ros-noetic-joint-state-publisher-gui
 
$ sudo apt-get install ros-noetic-gazebo-ros-control joint-state-publisher
 
$ sudo apt-get install ros-noetic-ros-controllers ros-noetic-ros-control
 
$ sudo nano ~/.bashrc
 
at the end of the (bashrc) file add the follwing line 
but change it to you name
 
source /home/hudaaziz/catkin_ws/devel/setup.bash
 
$ source ~/.bashrc
 
$ roslaunch robot_arm_pkg check_motors.launch

![task2](https://user-images.githubusercontent.com/101423450/182405506-da594ecf-52c2-466f-a350-77af7fbb3706.png)
