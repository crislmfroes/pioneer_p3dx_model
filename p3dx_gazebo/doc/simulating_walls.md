# simulate a world with closed walls

In order to simulate an indoor world, source your ROS environment and catkin workspace, and then launch pioneer3dx.launch with the map1_wo_robot world.

```console
foo@bar:~$ source /opt/ros/melodic/setup.bash
foo@bar:~$ source /path/to/catkin_ws/devel/setup.bash
foo@bar:~$ roslaunch p3x_gazebo pioneer3dx.launch world:=map1_wo_robot
```

![A Pioneer P3-DX robot inside Gazebo.](img/p3dx_gazebo.png "A Pioneer P3-DX robot inside Gazebo.")