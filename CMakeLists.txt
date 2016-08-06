# Created by Duncan Campbell

# Required minimum version of CMake
cmake_minimum_required(VERSION 3.5)

# Name the project
project(KAYAKLIB CXX)

# Add in the source directory to the project build tree
add_subdirectory(src)
add_subdirectory(examples EXCLUDE_FROM_ALL)
