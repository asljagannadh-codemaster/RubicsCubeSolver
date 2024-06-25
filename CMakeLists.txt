cmake_minimum_required(VERSION 3.28)
project(RubicsCubeSolver)

set(CMAKE_CXX_STANDARD 17)

add_executable(RubicsCubeSolver main.cpp
        GeniricRubicsCubeSolver.cpp
        GeniricRubicsCubeSolver.h
        RubiksCube_3drep.cpp
        RubiksCube1dArray.cpp
        RubiksCubeBitBoard.cpp
        DFSSolver.h
        BFSSolver.h
        IDAstarSolver.h
        IDFSSolver.h
        IDFSSolver.h
        IDFSSolver.h
        IDFSSolver.h
        IDFSSolver.h
        PatternDatabases/CornerDBMaker.cpp
        PatternDatabases/CornerDBMaker.h
        PatternDatabases/CornerPatternDatabase.cpp
        PatternDatabases/CornerPatternDatabase.h
        PatternDatabases/NibbleArray.cpp
        PatternDatabases/NibbleArray.h
        PatternDatabases/PatternDatabase.cpp
        PatternDatabases/PatternDatabase.h
        PatternDatabases/PermutationIndexer.h
        PatternDatabases/cmath.cpp
        PatternDatabases/cmath.h
)
