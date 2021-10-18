# udm_kajal_jyotika_square_move


cd catkin_ws/src

git clone https://github.com/jyotika02/udm_kajal_jyotika_square_move.git

catkin_make

roslaunch turtlebot3_gazebo turtlebot3_world.launch

roslaunch udm_square_move turtlebot3_navigation.launch map_file:=$HOME/map.yaml

rosrun udm_square_move movebase_square.py
