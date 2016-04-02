cmake_minimum_required(VERSION 3.3)
project(cube_rotate_clion)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

find_package(OpenGL REQUIRED)
include_directories(${OPENGL_INCLUDE_DIRS})

find_package(GLUT REQUIRED)
include_directories(${GLUT_INCLUDE_DIRS})

include_directories(cube_rotate)
add_subdirectory(cube_rotate)

