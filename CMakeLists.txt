cmake_minimum_required(VERSION 3.7)
project(tree7)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp)
aux_source_directory(. DIR_SRCS)
add_executable(tree7 ${DIR_SRCS})