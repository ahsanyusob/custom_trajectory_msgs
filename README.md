# custom_trajectory_msgs

This package provides custom trajectory messages in addition to the official [trajectory_msgs](https://github.com/ros2/common_interfaces/tree/rolling/trajectory_msgs).  

Linked to [PR#281](https://github.com/ros2/common_interfaces/pull/281).

## Messages (.msg)
* [BaseTrajectory](msg/BaseTrajectory.msg): A time-parameterized sequence of poses, velocities, and accelerations for a mobile robot base to follow, typically relative to a fixed global frame.
* [BaseTrajectoryPoint](msg/BaseTrajectoryPoint.msg): A single target pose, velocity, and acceleration for the robot base at a specific time from the start of the trajectory.

