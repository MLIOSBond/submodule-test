cmake_minimum_required(VERSION 3.5)

project(submodule-test LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(submodule-test
    src/somelib.cpp
    include/somelib.h
    )
