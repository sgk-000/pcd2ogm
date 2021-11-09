cmake_minimum_required(VERSION 2.8.3)
project(pcd2ogm)

find_package(catkin REQUIRED COMPONENTS
)

catkin_package()

install(
  DIRECTORY
    launch
    rviz
    config
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)