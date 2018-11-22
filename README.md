# RoboND-Map-My-World-Robot
This project uses Real-Time Appearance-Based Mapping (RTAB-Map) implementation of
Simultaneous Localization and Mapping (SLAM) in ROS to build both 2D occupancy grid map and 3D
octomaps from the provided simulated environment as well as personal built environment using
mobile robot. RTAB-Map SLAM algorithm uses data collected from vision sensor to localize the
robot and map the environment and also uses a process called loop closure to determine whether the robot has seen a location before.

## [Link to Rtabmap database in my Google Drive](https://drive.google.com/open?id=1a1bOgV17lL1ZaITwrdh_DuOibPiso5RU)

### How to clone this repository
```
$ cd ~/catkin_ws/src

$ git clone https://github.com/salabson/RoboND-Map-My-World-Robot.git
```

### How to use this repository
```
$ cd ~/catkin_ws/src/scripts
$ ./rtab_run.sh
Enter target world destination or d for default:
$ d
```

#### RTAB-Map Visualization Tools - Database Viewer
Stop mapping.launch in its termial and run below command:
`$ rtabmap-databaseViewer ~/.ros/rtabmap.db `
