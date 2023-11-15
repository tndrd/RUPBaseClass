cmake_minimum_required(VERSION 3.0)
project(RUPBaseClass CXX)

include_directories(Inc/)

add_library(RUPBaseClass Src/RUPBaseClass.cpp)
target_include_directories(RUPBaseClass PUBLIC Inc/)