# aiscbot
aiscbot 

This is for Nilesh Kekare

# INSTALLATION
sudo apt-get install ros-melodic-move-base ros-melodic-amcl  ros-melodic-rqt-image-view ros-melodic-navigation ros-melodic-joint-state-publisher ros-melodic-robot-state-publisher ros-melodic-joy ros-melodic-teleop-twist-joy ros-melodic-teleop-twist-keyboard ros-melodic-urdf ros-melodic-xacro

# MAPPING
roslaunch aiscbot_firmware bringup.launch

roslaunch aiscbot_firmware server_bringup.launch

roslaunch aiscbot_slam aiscbot_slam.launch

rosrun teleop_twist_keyboard teleop_twist_keyboard.py

roslaunch aiscbot_slam view_sensors.launch

sudo apt-get install ros-melodic-map-server

# NAVIGATION

roslaunch aiscbot_firmware bringup.launch

roslaunch aiscbot_firmware server_bringup.launch

roslaunch aiscbot_navigation aiscbot_navigation.launch

