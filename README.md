# perception_pcl
This repository is used to generate a fake laserscan signal from pointclouds for a segway platform in ROAHM Lab, University of Michigan.

I create several launch files for my own use, for example:
```
roslaunch pcl_ros zed_pointcloud_to_laser.launch
```

or

```
roslaunch pcl_ros fotonic_pointcloud_to_laser.launch

```

Note that this repository is pulled from perception_pcl package: https://github.com/ros-perception/perception_pcl.git

# Here starts their original README file
[![Build Status](https://travis-ci.org/ros-perception/perception_pcl.svg)](https://travis-ci.org/ros-perception/perception_pcl)

PCL (Point Cloud Library) ROS interface stack. PCL-ROS is the preferred
bridge for 3D applications involving n-D Point Clouds and 3D geometry
processing in ROS.
