# stair_traversal_tutorial
Repo providing a ROS workspace setup that allows for the simulation of a tracked robot capable of autonomous stair climbing

This repository provides a complete workspace setup for providing a simulated tracked robot that is capable of autonomous stair climbing in Gazebo simulation.


# Installation
Make sure you installed ROS Indigo as described in the [ROS Installation instructions](http://wiki.ros.org/indigo/Installation/Ubuntu).

Add the OSRF repository to your system to allow the use of newer Gazebo versions. This is described [here](http://gazebosim.org/tutorials?tut=install_ubuntu&cat=install).

Install a Gazebo version of your choice (The tutorial has been well tested with gazebo5):
```
sudo apt-get install ros-$ROS_DISTRO-gazebo5-ros ros-$ROS_DISTRO-gazebo5-plugins ros-$ROS_DISTRO-gazebo5-ros-control
```

Enter a folder of your choice (a good choice is the home folder) and check out this repo:
```
git clone https://github.com/tu-darmstadt-ros-pkg/autonomous_stair_traversal_tutorial.git
```
Enter folder and run the update script:
```
cd autonomous_stair_traversal_tutorial
./update.sh
```
The script creates a workspace, installs dependencies, clones multiple repositories and builds them using [catkin tools](https://catkin-tools.readthedocs.org/en/latest/quick_start.html)

# Usage

Further instructions on how to use the workspace will be added soon.
