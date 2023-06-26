cmake_minimum_required(VERSION 2.8.3)
project(pal_motion_loader)
find_package(catkin REQUIRED)
catkin_package()

install(PROGRAMS scripts/load_available_motions.py
  DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION}
)
