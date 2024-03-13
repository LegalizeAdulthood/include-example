cmake_minimum_required(VERSION 3.23)

set_property(GLOBAL PROPERTY USE_FOLDERS ON)

project(include-example CXX)

add_executable(include-example main.cpp)
set_target_properties(include-example PROPERTIES
    CXX_STANDARD 11
    CXX_STANDARD_REQUIRED ON)
