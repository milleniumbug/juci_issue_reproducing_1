cmake_minimum_required(VERSION 3.3)

project(sample_test)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11 -Wall")

include_directories(include)
add_executable(sample_test include/abcdef.hpp main.cpp)
