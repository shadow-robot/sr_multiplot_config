cmake_minimum_required(VERSION 2.8.3)
project(hand_h_multiplot)

find_package(catkin REQUIRED)

catkin_package(
)

include_directories(
)

## Mark other files for installation (e.g. launch and bag files, etc.)
install(DIRECTORY xml
    DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)