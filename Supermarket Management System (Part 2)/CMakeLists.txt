cmake_minimum_required(VERSION 3.28)
project(untitled2 C)

set(CMAKE_C_STANDARD 11)

add_executable(untitled2 main.c
        Column.c
        Column.h
        Dataframe.c
        Dataframe.h)
