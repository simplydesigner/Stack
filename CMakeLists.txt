cmake_minimum_required(VERSION 3.5)
project(Stack1)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES stack.cpp)
add_executable(Stack1 ${SOURCE_FILES})
