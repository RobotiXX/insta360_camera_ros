# insta360_camera_ros

This package provides integration for using Insta360 X4 cameras with the `camera_ros` package in ROS 2.  
It supports streaming the stitched 360° cylindrical view directly to ROS from the camera's webcam mode.

## Quickstart

1. Connect the Insta360 X4 camera to your computer via USB-C and set the camera to **webcam mode**.
2. Launch the ROS 2 launch file:
   ```bash
   ros2 launch insta360_camera_ros insta360_x4.launch.py