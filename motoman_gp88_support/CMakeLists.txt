cmake_minimum_required(VERSION 3.10.2)
project(motoman_gp88_support)

find_package(ament_cmake REQUIRED)

install(
  DIRECTORY config launch meshes urdf
  DESTINATION share/${PROJECT_NAME}
)

ament_package()