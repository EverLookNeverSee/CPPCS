cmake_minimum_required(VERSION 3.16)
project(CPPCS)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)
include_directories(src)

add_executable(CPPCS
        src/openMP/02_Integral.cpp)
