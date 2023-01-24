# Autonomous-Navigation

This repo consists of autonomous navigation and trajectory planning of a robot using Robot Operating System (ROS). A maze is created in gazebo for the robot to determine the best possible trajectory with collison avoidance. Probablistic localization method is used for navigation. Adaptive Monte Carlo Localization(AMCL) node and  slam_gmapping package is used for localization of robot and mapping of robot. Rviz interface is used for the simulation of robot and creating the cost map for the travel of robot.

To perform the simulation, open the terminal and use the code:

``` roslaunch autonomous_slam_navigation l4_robot_navigation.launch ``` 


Maze environemnt created in gazebo for path planing 
![Maze](https://user-images.githubusercontent.com/111289395/213635371-ecf19876-836f-47a3-92d9-0fd87604ce51.png)
![maze_01](https://user-images.githubusercontent.com/111289395/213635484-c3fa173b-6fb5-43c2-bc01-110047eb67cb.png)

Cost map created using Rviz
![cost_map](https://user-images.githubusercontent.com/111289395/213635605-f00a9df0-98d0-486d-82c0-411a63f98904.png)

Trajectory generated for different scenarios
![Navigation_01](https://user-images.githubusercontent.com/111289395/213635717-94e01e6f-b1e8-4ece-9a86-db6cc436425c.png)
![Navigation_02](https://user-images.githubusercontent.com/111289395/213635783-afff25da-b4c1-4ec6-a6f7-c462b26a54e6.png)
![Navigation_03](https://user-images.githubusercontent.com/111289395/213635824-80737c68-b929-4fd4-8005-09b7233c86d5.png)

