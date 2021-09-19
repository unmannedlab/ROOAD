<h1>ROOAD: RELLIS Off-road Odometry Analysis Dataset</h1>
<p align="center">
  George Chustz<sup>1</sup> and Srikanth Saripalli<sup>1</sup>
<p align="center">
  1. <a href="https://www.tamu.edu/">Texas A&M University; </a>
<p align="center"><a href="https://unmannedlab.github.io/research/ROOAD">[Website]</a> <a href="https://arxiv.org/">[Paper TBD]</a> <a href="https://github.com/unmannedlab/ROOAD">[Github]</a> 
<p align="center">[Download All] [Cite Us]
</p>

## Updates
9/15/2021 Initial release

## Overview

### Data Collection Platform

### Sensor Setup

### Calibration

### ROS Bag

Data included in raw ROS bagfiles:

Topic Name | Message Type | Message Descriptison
------------ | ------------- | ---------------------------------
/pylon_camera_node/image_raw | sensor_msgs/Image | Images from the Basler Pylon Camera
/vectornav/IMU | sensor_msgs/Imu | Imu data from VectorNav-VN300
/UBX/hpposllh | ubxtranslator/hpposllh | GPS data from the ground truth RTK GPS
/UBX/relpos2D | ubxtranslator/hpposllh |

ROS bag download links:
(rt4_gravel [8GB] (https://drive.google.com/file/d/1dKx6_A1V4wN_0NTKCLrWYgIwozsVrO0F/view?usp=sharing))
