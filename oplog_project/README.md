# OPLOG ROS PROJECT

Hi! Here is my ROS-Melodic 2 Wheel Robot Differential Drive project.
 
# How to compile the project ?
			 
After downloading the project move the project to the home directory.

    $ cd oplog_project
    $ catkin build
    $ echo "source ~/oplog_project/devel/setup.bash" >> ~/.bashrc
    $ source ~/.bashrc
    $ roslaunch mybot_gazebo mybot_world.launch

Gazebo will be launched. 

Open a second terminal to install and run teleop node.

    $ sudo apt-get install ros-melodic-teleop-twist-keyboard
    $ rosrun teleop_twist_keyboard teleop_twist_keyboard.py

[See the on-screen instructions for teleop ](https://drive.google.com/file/d/1R0J7RnHVt0V3nIoVpgzSwtaT7CjwmQCf/view?usp=sharing)
  
  In a third terminal, check what nodes are running.

 -  `$ rosnode list` : list active nodes 
 -  `$ rostopic list` : print information about active topics 
 
[rosnode list & rostopic list in terminal](https://drive.google.com/file/d/1sJgJZcWd5N0iQf7yPrIV8mTjIH2VTmmZ/view?usp=sharing)
  
