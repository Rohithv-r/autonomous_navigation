# autonomous_navigation
A Gazebo simulation of a mobile robot that can autonomously traverse to a destination point.

Here, a simple robot URDF is created using Solidworks. The robot is equipped with 2 ultrasonic sensors at the sides and a LIDAR mounted at the front.
The package uses the gmapping package to map a given world in Gazebo and then the amcl package is used to perform localization and finally the move_base package to perform path planning.
