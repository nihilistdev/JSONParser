cmake_minimum_required(VERSION 3.16)
project(JSONParser)

add_subdirectory(src)
set(CMAKE_CXX_STANDARD 14)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR})
set(CMAKE_BUILD_TYPE Debug)