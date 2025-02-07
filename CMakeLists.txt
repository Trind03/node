include(init.cmake)
cmake_minimum_required(VERSION 3.10)
project(node)

# Variable init
set(SOURCE_MAIN ${CMAKE_SOURCE_DIR}/src/main.cpp)

add_executable(${PROJECT_NAME} ${SOURCE_MAIN})
