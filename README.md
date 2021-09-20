<h1>ROOAD: RELLIS Off-road Odometry Analysis Dataset</h1>
<p align="center">
  George Chustz<sup>1</sup> and Srikanth Saripalli<sup>1</sup>
<p align="center">
  1. <a href="https://www.tamu.edu/">Texas A&M University; </a>
<p align="center"><a href="https://unmannedlab.github.io/research/ROOAD">[Website]</a> <a href="https://arxiv.org/abs/2109.08228">[Paper]</a> <a href="https://github.com/unmannedlab/ROOAD">[Github]</a> 
<p align="center">[Download All] <a href="https://github.com/unmannedlab/ROOAD/blob/main/bibtex_citation">[Cite Us]</a>
</p>

## Updates
9/15/2021 Initial release

## Overview

### ROS Bag

Data included in raw ROS bagfiles:

Topic Name | Message Type | Message Descriptison
------------ | ------------- | ---------------------------------
/pylon_camera_node/image_raw | sensor_msgs/Image | Images from the Basler Pylon Camera
/vectornav/IMU | sensor_msgs/Imu | Imu data from VectorNav-VN300
/UBX/hpposllh | ubxtranslator/hpposllh | GPS data from the ground truth RTK GPS
/UBX/relpos2D | ubxtranslator/hpposllh |

ROS bag download links:

rt4_calib  [6GB](https://drive.google.com/file/d/1IlHBodzK2GZYLctGTVceWP0uZ68y9hkt/view?usp=sharing)

rt4_gravel [8GB](https://drive.google.com/file/d/1dKx6_A1V4wN_0NTKCLrWYgIwozsVrO0F/view?usp=sharing)

rt4_rim    [5GB](https://drive.google.com/file/d/1m7y33UzYjT-1VgehGPSIzzcWltGRPb-N/view?usp=sharing)

rt4_updown [12GB](https://drive.google.com/file/d/1x-nKiURqvLhwyyHBCuPVEdS8MGo1VhOk/view?usp=sharing)

rt5_calib  [6GB](https://drive.google.com/file/d/19kQlU3PpkSEQdq1eZ4w7zs8GBo8p6jeO/view?usp=sharing)

rt5_gravel [7GB](https://drive.google.com/file/d/1NBq-YU0YYuI1-D8DxSXdBeoWQ9hCOfj0/view?usp=sharing)

rt5_rim    [5GB](https://drive.google.com/file/d/1sz33CuQ5rxQtYPe5DIpcOMTW9gpvu9Be/view?usp=sharing)

rt5_updown [10GB](https://drive.google.com/file/d/1Y1CjTEnbPadbg00uw0KLrydDc5-p9Cr0/view?usp=sharing)

## Cite Us
'''
@misc{chustz2021rooad,
      title={ROOAD: RELLIS Off-road Odometry Analysis Dataset}, 
      author={George Chustz and Srikanth Saripalli},      
      year={2021},      
      eprint={2109.08228},      
      archivePrefix={arXiv},      
      primaryClass={cs.RO}      
}
'''


