cmake_minimum_required(VERSION 3.0.0)
project(pud_description)

find_package(catkin REQUIRED)

catkin_package()

install(DIRECTORY meshes DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
install(DIRECTORY urdf DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
