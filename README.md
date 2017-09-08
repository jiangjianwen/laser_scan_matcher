# PLICP scan matcher for ROS
An incremental laser scan matcher, using PLICP (point-to-line iterative closest point) scan matching algorithm.

## How to use on Ubuntu?
    1. This package I have tested well on Ubuntu 16.04 LTS, and my version of ROS is kinetic.
    
    2. If you want to use it, you must install csm first:
        $ sudo apt-get install ros-kinetic-csm
        
    3. clone and cantkin_make
        $ cd catkin_ws/src/
        $ git clone https://github.com/WENJIAN0629/laser_scan_matcher
        $ cd..
        $ catkin_make
  

## Thanks

[1] A. Censi, "An ICP variant using a point-to-line metric" Proceedings of the IEEE International Conference on Robotics and Automation (ICRA), 2008

[2] https://github.com/ccny-ros-pkg/scan_tools

[3] https://github.com/ros-perception/open_karto

[4] https://github.com/ros-perception/slam_karto
