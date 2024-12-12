### Intro
Rviz is the primary visualizer in ROS and a very useful tool for debugging robotics. 
The MoveIt Display plugin allows you to setup virtual environments (planning scenes), create start and goal states for the robot interactively, test various motion planners, and visualize the output.

## TASK 1 2 3
launch the demo
```
ros2 launch moveit2_tutorials demo.launch.py
```
### functionalities
- Collision detection
- starting position
- goal position
- path planner

### NULL SPACE 
The null space of J is the subspace N (J ) in IRn of joint velocities that do
not produce any end-eﬀector velocity, in the given manipulator posture.

```
ros2 run hello_moveit hello_moveit
```

### Rviz limits
- programming advantages

KinematicConstraint.
JointConstraint,
PositionConstraint, 
OrientationConstraint

## TASK 4
change branch 
```
git checkout task 4
```
launch again demo and hello_moveit

#### Example 1
```
ros2 launch moveit2_tutorials planning_scene_tutorial.launch.py
```

#### Example 2
```
ros2 launch moveit2_tutorials move_group.launch.py
```
```
ros2 launch moveit2_tutorials planning_scene_ros_api_tutorial.launch.py
```

## Task 5
```
ros2 launch moveit_task_constructor_demo demo.launch.py
```
```
ros2 launch moveit_task_constructor_demo run.launch.py exe:=cartesian
ros2 launch moveit_task_constructor_demo run.launch.py exe:=modular
ros2 launch moveit_task_constructor_demo run.launch.py exe:=pick_place_demo
```

```
ros2 launch moveit2_tutorials mtc_demo.launch.py
```
```
ros2 launch mtc_tutorial pick_place_demo.launch.py
```