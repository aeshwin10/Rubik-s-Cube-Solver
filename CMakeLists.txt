cmake_minimum_required(VERSION 3.28)
project(Project_3)

set(CMAKE_CXX_STANDARD 17)

add_executable(Project_3 main.cpp
        Solver/BFSSolver.h
        Solver/DFSSolver.h
        Solver/IDAstarSolver.h
        Model/RubiksCube.cpp
        Model/RubiksCube.h
        Model/RubiksCube1dArray.cpp
        Model/RubiksCube1dArray.cpp
        Model/RubiksCube3dArray.cpp
        Model/RubiksCube3dArray.cpp
        Model/PatternDatabase/PatternDatabase.h
        PatternDatabases/CornerDBMaker.cpp
        PatternDatabases/CornerPatternDatabase.cpp
        PatternDatabases/CornerPatternDatabase.h
        PatternDatabases/NibbleArray.cpp
        PatternDatabases/NibbleArray.h
        PatternDatabases/NibbleArray.h
        PatternDatabases/PatternDatabase.cpp
        PatternDatabases/PermutationIndexer.h
        PatternDatabases/math.cpp
        PatternDatabases/math.h
        Model/RubiksCubeBitboard.cpp
        PatternDatabases/PatternDatabase.h
        PatternDatabases/CornerDBMaker.h
        Solver/IDDFSSolver.h)
