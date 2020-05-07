# simulate an empty world
In order to simulate an empty world, source your ROS environment and catkin workspace, and then launch pioneer3dx.launch.

```console
foo@bar:~$ source /opt/ros/melodic/setup.bash
foo@bar:~$ source /path/to/catkin_ws/devel/setup.bash
foo@bar:~$ roslaunch p3x_gazebo pioneer3dx.launch world:=p3dx
```