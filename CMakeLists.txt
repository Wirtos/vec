cmake_minimum_required(VERSION 3.10)
project(vec VERSION 0.1 LANGUAGES C)

set(CMAKE_C_STANDARD 99)
set(CMAKE_C_STANDARD_REQUIRED ON)
set(CMAKE_C_EXTENSIONS OFF)

add_library(vec src/vec.c)
target_include_directories(vec PUBLIC src)
