cmake_minimum_required(VERSION 3.19)
project(MAHashing C)

set(CMAKE_C_STANDARD 99)

add_executable(
        MAHashing
        bits.c
        bits.h
        buckets.c
        )