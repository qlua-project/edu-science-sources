cmake_minimum_required(VERSION 3.17)
project(edu_science_sources C)

set(CMAKE_C_STANDARD 99)

add_library(edu_science_sources SHARED library.c library.h)