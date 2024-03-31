project(Test)
cmake_minimum_required(VERSION 3.0)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

include_directories(public)

add_executable(my_test main.cpp private/wontFind.cpp public/wontFind.hpp)
