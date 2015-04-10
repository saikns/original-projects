cmake_minimum_required(VERSION 2.8)
SET(CMAKE_CXX_FILES "-g -Wall")

set(PROJECT_NAME cli_app)
PROJECT(${PROJECT_NAME})

set(EXECUTABLE_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/bin)
set(LIBRARY_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/lib)

set(SRC src/cli_main.cpp)

add_executable(${PROJECT_NAME} ${SRC})
target_link_libraries(${PROJECT_NAME} sorting)
target_link_libraries(${PROJECT_NAME} searching)
