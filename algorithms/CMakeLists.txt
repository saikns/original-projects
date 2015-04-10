project(algorithms)
cmake_minimum_required(VERSION 2.8)
SET(CMAKE_CXX_FLAGS "-g -Wall")
SET(BUILD_SHARED_LIBS ON)

ADD_SUBDIRECTORY(sorting)
ADD_SUBDIRECTORY(searching)
ADD_SUBDIRECTORY(cli_app)
