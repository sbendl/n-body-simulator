cmake_minimum_required(VERSION 3.8)
project(nbody)

set(CMAKE_CXX_STANDARD 17)

set(SOURCE_FILES main.cpp)
add_executable(nbody ${SOURCE_FILES})