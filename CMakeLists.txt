cmake_minimum_required (VERSION 3.0.0)
project (Hello_Jenkins)

set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_SOURCE_DIR}/bin)

add_executable(hello_jenkins src/main.cpp)