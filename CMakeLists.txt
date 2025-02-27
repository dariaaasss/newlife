cmake_minimum_required(VERSION 3.10)

project(newlife)

set(CMAKE_CXX_STANDART 11)
set(CMAKE_CXX_STANDART_REQUIRED True)

include_directories(src)

add_executable(newlife src/main.cpp src/utils.cpp src/utils.hpp)