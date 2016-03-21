cmake_minimum_required(VERSION 2.8)
SET(CMAKE_CXX_FILES "-g -Wall")

set(PROJECT_NAME perception)
PROJECT(${PROJECT_NAME})

set(INCLUDE ${CMAKE_CURRENT_SOURCE_DIR}/include)
include_directories(${INCLUDE})

set(EXECUTABLE_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/bin)
set(LIBRARY_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/lib)

set(SRC src/main.cpp)

add_executable(${PROJECT_NAME} ${SRC})
