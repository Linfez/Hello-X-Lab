cmake_minimum_required(VERSION 3.27)

PROJECT (main)
SET(SRC_LIST main.c print1.c print.c)
message(STATUS "This is BINARY dir" ${PROJECT_BINARY_DIR})
message(STATUS "This is SOURCE dir" ${PROJECT_SOURCE_DIR})
add_executable(main ${SRC_LIST})