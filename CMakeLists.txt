cmake_minimum_required(VERSION 3.10)

set (CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++14")
set (CMAKE_EXPORT_COMPILE_COMMANDS ON)

project(cmake-template)

enable_testing()

add_subdirectory( main )
add_subdirectory( modules )

