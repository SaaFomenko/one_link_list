cmake_minimum_required(VERSION 3.30)

project(one_link_list)

# set the C++ standard
set(CMAKE_CXX_STANDARD 11)

set(CMAKE_WINDOWS_EXPORT_ALL_SYMBOLS ON)

add_executable(test main.cpp)