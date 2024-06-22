cmake_minimum_required(VERSION 3.28)
project(RubicsCubeSolver)

set(CMAKE_CXX_STANDARD 17)

add_executable(RubicsCubeSolver main.cpp
        GeniricRubicsCubeSolver.cpp
        GeniricRubicsCubeSolver.h
        RubiksCube_3drep.cpp
)
