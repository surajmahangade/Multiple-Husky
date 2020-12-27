# Multiple-Husky
Repository contains multiple husky simulation and navigation in ros melodic and ros noetic
## Note
* The repository assumes that you have all the dependency pacakges like robot_localization,twist_mux,interactive_marker_twist_server,unique_identifier and so on installed properly.
### Create workspace and git clone the repository
* `mkdir -p ~/catkin_ws/src`
* `cd ~/catkin_ws/src`
* `git clone https://github.com/surajmahangade/Multiple-Husky.git`
* `git checkout noetic`
* `cd ..`
#### You can clone the repositories of rosbo_localization,twist whichever not installed,like.
* `git clone https://github.com/cra-ros-pkg/robot_localization.git`
#### Checkout the right branch 
* `git checkout noetic-devel`
#### catkin make
* `cd ~/catkin_ws`
* `catkin_make`
#### source and launch
* `source devel/setup.bash`
* `roslaunch aws_robomaker_small_warehouse_world multihusky.launch`

