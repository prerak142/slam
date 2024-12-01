# slam
source /opt/ros/humble/setup.bash
sudo apt install ros-humble-navigation2 ros-humble-nav2-bringup ros-humble-turtlebot3*

turtlebot 3

gedit ~/.bashrc

sudo apt install if gedit is not recognized

export TURTLEBOT3_MODEL=waffle  in source file 


ros2 launch turtlebot3_gazebo turtlebot3_world.launch.py

![image](https://github.com/user-attachments/assets/952b9e07-0ace-44c6-9cba-8245532c179e)

first time it will take time to load 


slam


ros2 launch turtlebot3_gazebo turtlebot3_world.launch.py


ros2 launch turtlebot3_cartographer cartographer.launch.py use_sim_time:=True


ros2 run turtlebot3_teleop teleop_keyboard
