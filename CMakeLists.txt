cmake_minimum_required(VERSION 3.22)
project(advanced_objective_training_config)

find_package(ament_cmake REQUIRED)

install(
  DIRECTORY
    config
    objectives
    waypoints
  DESTINATION
    share/${PROJECT_NAME}
)


ament_package()
