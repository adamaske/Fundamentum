cmake_minimum_required(VERSION 3.15)
include(cmake_functions.cmake)

project(Fundamentum VERSION 1.0)

set(${CMAKE_RUNTIME_OUTPUT_DIRECTORY} ${PROJECT_BINARY_DIR})
set(${CMAKE_ARCHIVE_OUTPUT_DIRECTORY} ${PROJECT_BINARY_DIR})
set(${CMAKE_LIBRARY_OUTPUT_DIRECTORY} ${PROJECT_BINARY_DIR})

add_subdirectory(deps)
add_subdirectory(vendor)
add_subdirectory(src)

