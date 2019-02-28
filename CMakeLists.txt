cmake_minimum_required(VERSION 3.12.3)

project(Smart)
SET(CMAKE_CXX_FLAGS "-std=c++11 ${CMAKE_CXX_FLAGS}")
SET(CMAKE_C_COMPILER g++)
add_compile_options(-std=c++11)
add_subdirectory(OS)
