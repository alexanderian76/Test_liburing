cmake_minimum_required(VERSION 3.25)
project(Test VERSION 1.0.0 LANGUAGES C)

set(CMAKE_EXE_LINKER_FLAGS "-luring")

add_executable(tcp main.c)
