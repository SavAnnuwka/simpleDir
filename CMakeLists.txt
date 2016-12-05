cmake_minimum_required(VERSION 3.3)
project(simpleDir)
add_subdirectory(simple123)
add_subdirectory(simple2)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp simple123/first.cpp simple2/second.cpp)
add_executable(simpleDir ${SOURCE_FILES})