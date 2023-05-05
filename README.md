# Micromouse-Path-Planning-SImulation
To make the micromouse robot capable of reaching the centre of the given maze in the shortest possible time using maze solving algorithms.

## Introduction
The maze solving has gained increasing attention in the field of Micromouse competition and Intelligent Robot.
The goal for Micromouse maze solving is to reach the destination cell with minimum cost of resources, such as time and steps. The Micromouse is an automated robot which has to find its way through the arbitrary maze within the least amount of time.
In this simulation, we aim to model the maze layout and obstacles, as well as the robot's sensors and actuators. This simulation will provide valuable insights into the behavior of the robot in a controlled environment and will help us to improve the performance of the actual robot when navigating through a real-world maze.

## Technologies Used
[![Tech_Used](https://skills.thijs.gg/icons?i=py,ROS,Gazebo&theme=dark)](https://skills.thijs.gg)

## Installation

```sh
git clone https://github.com/devgoti16/Micromouse-Path-Planning-SImulation.git
```
Add this folder in the src directory of your catkin workspace
Create the src folder if it doesn't already exist by
```sh
mkdir src
```
Initialise the project with
```sh
catkin_make
source /opt/ros/noetic/setup.bash      #run this and the command below everytime
source ~/catkin_ws/devel/setup.bash     you need to launch nodes 
```

### Execution
Open two terminal windows and run the following commands
- Terminal 1
```sh
source /opt/ros/noetic/setup.bash
source ~/catkin_ws/devel/setup.bash
roslaunch pkg_techfest_imc final.launch
```
- Terminal 2
```sh
source /opt/ros/noetic/setup.bash
source ~/catkin_ws/devel/setup.bash
rosrun pkg_techfest_imc final.py
```

## Implementation
![image](https://user-images.githubusercontent.com/82582574/236429137-54a97e09-fb81-4efe-807e-6016c63b1276.png)


## Future Work
- [ ] Write a code for PID to make sure the bot remains a the centre of the path
- [ ] Implement other algorithms
- [ ] Learn about gzmaze so that a maze of any desired structure can be generated



## Project Mentors

1. [Dev Goti](https://github.com/devgoti16)
2. [Pooja M](https://github.com/Pooja-murugiah)

## Project Mentees
1. Hemang Jamadagni
2. [Madhav Kedia](https://github.com/madhavkedia018)
3. Pushkaran D
4. Adithya Ubaradka
