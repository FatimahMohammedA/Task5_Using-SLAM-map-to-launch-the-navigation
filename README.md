# Task5_Using-SLAM-map-to-launch-the-navigation

1-Launch Simulation World:

$ export TURTLEBOT3_MODEL=burger

$ roslaunch turtlebot3_gazebo turtlebot3_world.launch

![Screen Shot 1443-01-07 at 1 46 56 PM](https://user-images.githubusercontent.com/86549177/129480609-7778575b-c49b-4895-bac1-112dc2735b9c.png)



<img width="975" alt="Screen Shot 1443-01-07 at 1 57 57 PM" src="https://user-images.githubusercontent.com/86549177/129480630-bcafabbb-7e17-4c7b-a97e-f0be96f86e0d.png">


<img width="1379" alt="Screen Shot 1443-01-07 at 3 34 19 PM" src="https://user-images.githubusercontent.com/86549177/129480652-eea341d4-b5f9-4af5-9ed3-f00243fb6cb4.png">

2-Run Navigation Node:

$ export TURTLEBOT3_MODEL=burger

$ roslaunch turtlebot3_navigation turtlebot3_navigation.launch map_file:=$HOME/map.yaml


3-Estimate Initial Pose:

<img width="1379" alt="SLAM2" src="https://user-images.githubusercontent.com/86549177/129480695-833efc36-aafd-4181-9b5b-34740022c997.png">




