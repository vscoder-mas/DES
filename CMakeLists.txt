cmake_minimum_required(VERSION 3.21)
project(DES C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(DES
        des.c
        des.h
        run_des.c)
