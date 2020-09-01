robot_localization for dashing
==================

Using parameter for dashing: 

https://index.ros.org//doc/ros2/Releases/Release-Dashing-Diademata/#declaring-parameters

### prerequisites
1. clone diagnostics repository(**crystal**, not dashing)
```bash
$ cd ~/ros2_ws/src
$ git clone https://github.com/ros/diagnostics.git -b crystal
```
2. build
```bash
$ cd ~/ros2_ws
$ colcon build --symlink-install
$ . install/setup.bash
```

# Original
## robot_localization

robot_localization is a package of nonlinear state estimation nodes. The package was developed by Charles River Analytics, Inc.

Please see documentation here: http://wiki.ros.org/robot_localization
