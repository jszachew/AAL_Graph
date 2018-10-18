# cmake_minimum_required(VERSION <specify CMake version here>)
project(untitled)

set(CMAKE_CXX_STANDARD 14)

add_executable(untitled main.cpp cmake-build-debug/Graph.cpp cmake-build-debug/Graph.h cmake-build-debug/Vertex.cpp cmake-build-debug/Vertex.h)