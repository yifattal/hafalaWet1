cmake_minimum_required(VERSION 3.19)
project(hafalaWet1)

set(CMAKE_CXX_STANDARD 11)

add_executable(hafalaWet1 smash.cpp signals.cpp signals.h Commands.cpp Commands.h)