# aiscbot
aiscbot 

This is for Nilesh Kekare

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

