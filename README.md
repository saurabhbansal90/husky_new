# husky_rl
Using q-learning for path planning with husky

# Required Packages
sudo apt-get install libarmadillo*

# Open 4 Terminals and Enter below commands
roslaunch husky_gazebo husky_test_world.launch

roslaunch husky_viz view_robot.launch

roslaunch obstacle_detector nodes.launch

rosrun teleop_twist_keyboard teleop_twist_keyboard.py

# In RViz, add topic /obstacles 
