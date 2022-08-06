cmake_minimum_required(VERSION 3.22)
project(dtimer C)

set(CMAKE_C_STANDARD 11)

include_directories(./)
add_library(dtimer STATIC dtimer.c)
#add_executable(test test.c dtimer.c)