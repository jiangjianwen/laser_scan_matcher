# Laser Scan Matcher for ROS
The repo is the implementation of Point-to-Line Iterative Closest Point (PL-ICP) algorithm proposed by Censi [1]. The original code can be found in [2]. However, there are some bug about ROS tf transform in the original code. I fixed the bug and added the mapping module following the programming habits in open karto library [3].

## How to use on Ubuntu?
    1. This package has been tested well on Ubuntu 16.04 LTS, and the version of ROS is kinetic.
    
    2. If you want to use it, you must install csm first:
        $ sudo apt-get install ros-kinetic-csm
        
    3. clone and catkin_make
        $ cd catkin_ws/src/
        $ git clone https://github.com/WENJIAN0629/laser_scan_matcher
        $ cd..
        $ catkin_make
  

## Thanks

[1] A. Censi, "An ICP variant using a point-to-line metric," in *IEEE International Conference on Robotics and Automation (ICRA)*, 2008, pp. 19-25.

[2] https://github.com/ccny-ros-pkg/scan_tools

[3] https://github.com/ros-perception/open_karto
