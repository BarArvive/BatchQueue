cmake_minimum_required(VERSION 3.13)
project(BatchQueue)
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -pthread")
set(SOURCE_FILES evaluation.cpp postOffice.cpp headers/Testing.h)
add_executable(BatchQueue ${SOURCE_FILES})