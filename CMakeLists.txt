cmake_minimum_required(VERSION 4.4)
project(stm32 C)

set(CMAKE_C_STANDARD 11)

add_library(stm32 STATIC library.c)
