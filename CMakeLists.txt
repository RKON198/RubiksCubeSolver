cmake_minimum_required(VERSION 3.30)
project(RubiksCubeSolver)

set(CMAKE_CXX_STANDARD 14)

add_executable(RubiksCubeSolver main.cpp
        Model/GenericRubiksCube.cpp
        Model/GenericRubiksCube.h
        Model/RubiksCube3dArray.cpp
        Solver/DFSSolver.h
        Solver/BFSSolver.h
        Solver/IDDFSSolver.h
        Solver/IDAstarSolver.h
)
