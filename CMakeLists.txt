cmake_minimum_required(VERSION 3.25)
project(EE_367_Lab C)

set(CMAKE_C_STANDARD 99)

add_executable(prog prog.c)

add_executable(inf inf.c)

add_executable(segfault segfault.c)