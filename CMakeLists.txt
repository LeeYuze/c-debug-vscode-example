cmake_minimum_required(VERSION 3.0)
project(debug)
file(GLOB SRC_FILE *.c)
add_executable(${PROJECT_NAME} ${SRC_FILE})