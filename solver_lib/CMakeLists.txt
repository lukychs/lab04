cmake_minimum_required(VERSION 3.4)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_STANDARD 14)

project(solver_lb)
add_library(solver_lb STATIC ${CMAKE_CURRENT_SOURCE_DIR}/solver.cpp)
include_directories(${CMAKE_CURRENT_SOURCE_DIR})
