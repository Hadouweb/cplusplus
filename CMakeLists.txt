cmake_minimum_required(VERSION 3.7)
project(cplusplus)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES Assert.cpp)
add_executable(cplusplus ${SOURCE_FILES})