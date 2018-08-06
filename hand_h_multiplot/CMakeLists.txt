cmake_minimum_required(VERSION 2.8.3)
project(hand_h_multiplot)

find_package(catkin REQUIRED)

catkin_package(
)

include_directories(
)

## Mark other files for installation (e.g. launch and bag files, etc.)
install(FILES
    xml/All_encoders.xml
    xml/F0_encoders.xml
    xml/F1_encoders.xml
    xml/F2_encoders.xml
    xml/Torque_control.xml
    xml/motor_temp_current.xml
    DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION/xml}
)