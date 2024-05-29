cmake_minimum_required(VERSION 3.26)
project(LABA14 C)

set(CMAKE_C_STANDARD 11)

add_executable(LABA14 main.c
        libs/data_structures/vector/vector.c
        libs/data_structures/vector/vector.h)
