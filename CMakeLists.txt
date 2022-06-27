cmake_minimum_required(VERSION 3.5)
project(bob_description)

find_package(ament_cmake REQUIRED)

install(
  DIRECTORY config ros2_control urdf launch
  DESTINATION share/${PROJECT_NAME}
)

ament_package()
