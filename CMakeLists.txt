cmake_minimum_required(VERSION 3.7)
project(pathassociation)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_FLAGS "-fopenmp -std=c++0x")

set(SOURCE_FILES
        main.cpp
        graph.cpp
        graph.h
        utility.h associationrulemining.cpp
        associationrulemining.h)
add_executable(pathassociation ${SOURCE_FILES})