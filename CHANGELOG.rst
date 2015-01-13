^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package husky_description
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.0.3 (2015-01-13)
------------------
* Major refactor for indigo release:
  * base_link is now located on the ground plane, while chassis_link 
  * refactored joint names for consistency with Jackal and Grizzly for ros_control
  * moved plugins requiring gazebo dependencies to husky_gazebo (imu, gps, lidar, ros_control)
  * initial prefixing for multirobot
* Contributors: Alex Bencz, James Servos, Mike Purvis, Paul Bovbel, Prasenjit Mukherjee, y22ma

0.0.2 (2013-09-30)
------------------
* Renamed /models folder to /meshes to follow the convention of other gazebo simulation packages.
* Changed the base.urdf.xacro to use base_footprint as the parent frame. For some reason, the new Gazebo paints all parts the same color as base_link when base_link is the parent.

0.0.1 (2013-09-11)
------------------
* Move to model-only launchfile.
* Catkinize package, add install targets.
* husky_description moved up to repository root.
