# LIO-SAM_MID360_ROS2_PKG

### Dependency
 - autorccar_interfaces
 - livox_ros_driver2 
 - liovx MID360 (Hardware)

### Build
Run `build_ros2.sh` for the first build. It correctly builds the Livox package.


### Run
```bash
ros2 launch livox_ros_driver2 msg_MID360_launch.py

ros2 launch lio_sam run.launch.py
