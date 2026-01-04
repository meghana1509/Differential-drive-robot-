# Differential-drive-robot-
ROS 2 differential drive robot simulation using URDF, visualized in RViz. This project demonstrates basic robot modeling, coordinate frames, and ROS 2 launch setup as a foundation for mobile robotics applications.

## Features
- Differential drive base
- URDF-based robot description
- TF frames visualization
- RViz visualization using robot_state_publisher

## Tools & Technologies
- ROS 2 Humble
- URDF
- RViz2

## Visualization
<img width="1296" height="745" alt="image" src="https://github.com/user-attachments/assets/2c36dc96-2573-4975-86e5-de326b6e3256" />


## How to Run
```bash
cd ~/ros2_ws
source /opt/ros/humble/setup.bash
colcon build
source install/setup.bash
ros2 launch <package_name> display.launch.py

