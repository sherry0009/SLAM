cmake_minimum_required(VERSION 2.8)

project(EigenMatrix)

add_executable(eigenMatrix eigenMatrix.cpp)
include_directories("/usr/include/eigen3")

set(CMAKE_BUILD_TYPE "Debug")