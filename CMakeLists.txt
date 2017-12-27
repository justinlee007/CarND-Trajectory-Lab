cmake_minimum_required(VERSION 3.7)
project(CarND_Trajectory_Lab)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES src/main.cpp src/hybrid_breadth_first.cpp src/hybrid_breadth_first.h)
add_executable(CarND_Trajectory_Lab ${SOURCE_FILES})