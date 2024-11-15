# eut_ros2_control_repos
This package aims to provide only the ros2_control_repos under humble version.

The only difference w.r.t. the main fork is due to the gazebo_ros2_control which is the one taken from my personal repos.

```bash
cd eut_ros2_control_repos
vcs import . < eut_ros2_control_demos.$ROS_DISTRO.repos
rosdep update --rosdistro=$ROS_DISTRO
sudo apt-get update
```
