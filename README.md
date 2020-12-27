# Multiple-Husky
Repository contains multiple husky simulation and navigation in ros melodic and ros noetic
* Note the repository assumes that you have all the dependency pacakges like robot_localization,twist_mux,interactive_marker_twist_server and so on installed properly.
* `mkdir -p ~/catkin_ws/src`
* `cd ~/catkin_ws/src`
* `git clone https://github.com/surajmahangade/Multiple-Husky.git`
* `git checkout melodic`
* `cd ~/catkin_ws`
* `catkin_make`
* `source devel/setup.bash`
* `roslaunch aws_robomaker_small_warehouse_world multihusky.launch`
