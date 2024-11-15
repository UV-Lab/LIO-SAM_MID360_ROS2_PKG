# LIO-SAM_MID360_ROS2_PKG

### Dependency
We require the livox MID360 hardware.
```bash
## LIO-SAM (ros2)
sudo apt install -y ros-humble-perception-pcl \
  	   ros-humble-pcl-msgs \
  	   ros-humble-vision-opencv \
  	   ros-humble-xacro

## LIO-SAM (gtsam)
sudo add-apt-repository ppa:borglab/gtsam-release-4.1
sudo apt install -y libgtsam-dev libgtsam-unstable-dev
```

### Build
Run `build_ros2.sh` for the first build. It correctly builds the Livox package.


### Run
```bash
ros2 launch livox_ros_driver2 msg_MID360_launch.py

ros2 launch lio_sam run.launch.py
```
