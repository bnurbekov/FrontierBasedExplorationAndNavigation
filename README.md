Synopsis
========
This project implements a Software system for navigation and frontier based exploration for mobile robotic platforms (Turtlebots).

Installation
============
Save this package into catkin_ws/src/.

Run gazebo simulation by running 'roslaunch turtlebot_gazebo turtlebot_world.launch' or bringing up the actual turtlebot.

In a new tab, run 'rosrun rviz rviz'.

Open the final.rviz settings located in the 'rviz' folder.

Then run the following commands:
1) Run 'roslaunch final_project final_project.launch'
2) Run 'rosrun final_project mapping.py'. This will run the mapping service.
3) Run 'rosrun final_project control.py'. This will run the control script.

