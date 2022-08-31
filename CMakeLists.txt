cmake_minimum_required(VERSION 3.2)

project(tiny_ui)

set(SOURCE src/main.cpp)

add_executable(${PROJECT_NAME} WIN32 ${SOURCE})