cmake_minimum_required(VERSION 2.8.3)
project(roboskel_ros_resources)

find_package(catkin REQUIRED)

catkin_package()

include_directories()

install(DIRECTORY
    3d_models
    gazebo
    graspit
    DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)

