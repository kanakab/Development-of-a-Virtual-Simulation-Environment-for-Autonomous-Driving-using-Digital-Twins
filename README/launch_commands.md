* ## ROS Bridge:

1. Source the Terminal

       source /opt/ros/melodic/setup.bash
       source ~/carla-ros-bridge/catkin_ws/devel/setup.bash

2. Export Pythonpath to point at correct egg file and test the installation:

        export PYTHONPATH=$PYTHONPATH:/home/carissma-c301/carla/PythonAPI/carla/dist/carla-0.9.10-py2.7-linux-x86_64.egg
        python2 -c 'import carla;print "Success"'

3. Launch options

        roslaunch carla_ros_bridge carla_ros_bridge.launch
        roslaunch carla_ros_bridge carla_ros_bridge_with_rviz.launch
        roslaunch carla_ros_bridge carla_ros_bridge_with_example_ego_vehicle.launch


