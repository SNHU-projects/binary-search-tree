cmake_minimum_required(VERSION 3.15)
project(Lab6_2)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(Lab6_2
        BinarySearchTree.cpp
        CSVparser.cpp
        CSVparser.hpp)

