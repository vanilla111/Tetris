cmake_minimum_required(VERSION 3.7)
project(tetris)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        include/cubePoint.h
        include/cur.h
        include/game.h
        include/graph.h
        include/rand.h
        include/score.h
        src/cubePoint.cpp
        src/cur.cpp
        src/game.cpp
        src/graph.cpp
        src/rand.cpp
        src/score.cpp)

add_executable(tetris ${SOURCE_FILES})