cmake_minimum_required(VERSION 3.6)
project(CommNetsProject)

set(CMAKE_C_STANDARD 99)

set(SOURCE_FILES main.c IntermediateServer.c client.c)
add_executable(CommNetsProject ${SOURCE_FILES})