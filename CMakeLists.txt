cmake_minimum_required(VERSION 2.8)
project(testzecora)

set(CMAKE_CXX_STANDARD 14)

add_library(${PROJECT_NAME} library.cpp library.h)
