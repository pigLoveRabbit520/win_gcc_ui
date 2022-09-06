cmake_minimum_required(VERSION 3.2)

project(tiny_ui)

include_directories(${CMAKE_CURRENT_LIST_DIR}/include)  # 让 CMake 找到头文件

set(SOURCE src/main.cpp)

add_compile_definitions(UNICODE=1) # 启用unicode

add_executable(${PROJECT_NAME} WIN32 ${SOURCE})