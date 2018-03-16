cmake_minimum_required(VERSION 3.0)
project(testC)

set(CMAKE_CXX_STANDARD 11)

set(EXECUTABLE_OUTPUT_PATH bin)
set(SOURCE_FILES main.cpp)
add_executable(testC ${SOURCE_FILES})