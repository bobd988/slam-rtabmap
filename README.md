
## Project Setup and run
This project is the SLAM project of the Udacity Robotics Software Engineer Nanodegree.  With data from robot sensors and odometry data , using RTAB-Map ROS library database of environments were built, and both 2D and 3D maps were generated

To run the mapping process for kitchen world open up 4 terminals and run following commands seperately:
```
$ cd ~/catkin_ws
$ roslaunch slam_project world.launch
$ roslaunch slam_project teleop.launch
$ roslaunch slam_project mapping.launch
$ roslaunch slam_project rviz.launch
```
Then on the terminal that run teleop.launch move robot around the map using keyboard to map the world
![Alt text](./images/kitchen-gazebo.png?raw=true "Title")



To run the mapping process for  myworld open up 4 terminals and run following commands seperately:
```
$ cd ~/catkin_ws
$ roslaunch slam_project myworld.launch
$ roslaunch slam_project teleop.launch
$ roslaunch slam_project mapping.launch
$ roslaunch slam_project rviz.launch
```


![Alt text](./images/kitchen-RTAP.png?raw=true "Title")


![Alt text](./images/kitchen-rviz.png?raw=true "Title")
