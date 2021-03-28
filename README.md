# RoboND - KUKA Path Planning

---

Plan a path through a maze for an industrial KUKA Manipulator Arm!

### Dependencies

- ROS Kinetic

### Installation

``` bash
$ cd <repo-root>
$ git submodule update --init --recursive
```

### Build

``` bash
$ cd <repo-root>/catkin_ws
$ rosdep install --from-paths ./src --ignore-pacakges-from-source -y
$ catkin_make
```

### Running the program

```$  bash
$ cd <repo-root>/catkin_ws/src/rll_planning_project/scripts/
$ sh start_project.sh
```

