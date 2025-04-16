Folders and files explanation
.vscode, build, install, log:  autocreated, do nothing
src:      contains pkg
- rmit_description:
    - launch/gazebo.launch.py:  added gz_ros2_bridge for gazebo sim_time to ros2 and imu message
    - urdf: 
        - rmitbot.urdf.xacro:   imu_link, imu_joint added
        - rmitbot_gazebo.xacro: imu_pluggins added
- rmit_controller:  
    - no change
- rmit_localization:  
    - config/ekf.yaml
    - launch/local_localization.launch.py

