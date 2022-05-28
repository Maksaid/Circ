cmake_minimum_required(VERSION 3.20)
project(Lab7)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(Lab7
        buffer_exceptions.h
        circular_buffer.h
        main.cpp)
