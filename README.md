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



to save the map generated 
error aaya to run it again multiple times 

ros2 run nav2_map_server map_saver_cli -f maps/my_map



error faced 


sudo apt install ros-humble-rmw-cyclonedds-cpp
![image](https://github.com/user-attachments/assets/9f0fc051-b072-4f9c-8f49-201a2aeb8ab0)


dont ugrade update again
![image](https://github.com/user-attachments/assets/e5fdabe0-96da-45a6-a284-ae9c333c6d37)
![image](https://github.com/user-attachments/assets/9b5a14cc-7890-48d9-94d4-db30a7b2696f)
