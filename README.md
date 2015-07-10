# my-pick-challenge
My repo for implementing a robot for amazon picking challenge (developed under Ubuntu 12.04 + ROS Groovy)

##Challenge Details
http://amazonpickingchallenge.org/details.shtml

##TODO

###Environment Setup
1. Put the shelf and objects inside Gazebo
2. Place PR2 in front of the shelf
3. Save the world file

###Object Recognition 
1. Setup ORK for recognition
2. Add objects in the DB
3. Try linemod and other algorithm to recognize them

###Motion Planning
1. Setup MoveIt! by MoveIt! setup wizard
2. Integrate ORK's message and MoveIt!
   https://github.com/Po-Jen/convertmsg_orktomoveit

###Grasping
1. Further study on catkinized GraspIt! or try moveit_simple_grasps in ROS Hydro
https://github.com/davetcoleman/moveit_simple_grasps
