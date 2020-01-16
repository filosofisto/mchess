cmake_minimum_required(VERSION 3.12)
project(mchess)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(mchess
        ai.cc
        ai.h
        CBoard.cc
        CBoard.h
        CMove.cc
        CMove.h
        CMoveList.cc
        CMoveList.h
        CSquare.h
        main.cc)
