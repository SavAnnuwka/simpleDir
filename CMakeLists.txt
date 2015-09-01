cmake_minimum_required(VERSION 3.3)
project(simpleDir)
add_subdirectory(simple)
add_subdirectory(simple2)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp)
add_executable(simpleDir ${SOURCE_FILES})