cmake_minimum_required(VERSION 3.0.2)
project(robotics_hackathon_automation)


find_package(catkin REQUIRED COMPONENTS
  roscpp
  rospy
)

catkin_package()

include_directories(
# include
  ${catkin_INCLUDE_DIRS}
)
