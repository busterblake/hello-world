cmake_minimum_required(VERSION 3.27)
project(hello_world)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(hello_world
        main.cpp
        main.h)
