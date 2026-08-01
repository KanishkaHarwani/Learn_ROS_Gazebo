## Robot Package Template

This repository contains complete robot packages used throughout the learning process. Each module is self-contained and includes all the files required to build, run, and experiment with that specific robot. To keep the repository organized and make individual modules easy to download, every completed module is also provided as a compressed ZIP archive.

### Package Structure

Each completed robot package is stored as a separate ZIP file containing its complete ROS workspace, source code, URDF/Xacro files, launch files, configuration files, and assets (where applicable).



### Available Packages

#### `basic_rviz_urdf_tutorial.zip`

A beginner-friendly URDF project focused on understanding robot modeling and visualization in RViz.

**Contents**

* 3-DOF robotic arm
* Complete URDF description
* RViz visualization setup
* Basic joint hierarchy
* Link and joint definitions
* Materials and colors
* Example launch files

**Learning Objectives**

* Understand the structure of a URDF
* Create links and joints
* Define robot kinematics
* Visualize robots in RViz
* Build simple articulated robots

---

#### `articubot_one_basic_v1.zip`

The first version of a mobile robot based on the Articulated Robotics tutorial series.

**Robot Configuration**

* Differential drive (2 powered wheels)
* 1 caster wheel for stability
* Main chassis
* LiDAR sensor *(currently included for modeling only; not yet functional in simulation)*

**Contents**

* Complete robot description
* URDF/Xacro files
* Meshes and materials
* Launch files
* RViz configuration
* Gazebo-compatible package structure
* Robot assets

**Learning Objectives**

* Design a mobile robot using URDF/Xacro
* Build a differential-drive robot
* Add sensors to a robot model
* Organize ROS packages
* Prepare a robot for Gazebo simulation

> **Note:** The LiDAR is currently present in the robot model but has not yet been configured to publish scan data. Sensor plugins and ROS integration will be added in a future version.
