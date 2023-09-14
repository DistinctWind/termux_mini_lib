cmake_minimum_required(VERSION 3.27)
project(termux_mini_lib C)

set(CMAKE_C_STANDARD 11)

add_library(termux_mini_lib SHARED library.c)
install(TARGETS termux_mini_lib DESTINATION ${CMAKE_BINARY_DIR})