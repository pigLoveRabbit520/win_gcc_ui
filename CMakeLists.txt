cmake_minimum_required(VERSION 3.2)

project(tiny_ui)

include_directories(${CMAKE_CURRENT_LIST_DIR}/include)  # 让 CMake 找到头文件

set(CMAKE_BUILD_TYPE "Release")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++17")
set(CMAKE_CXX_FLAGS_RELEASE, "${CMAKE_CXX_FLAGS_RELEASE} -O3 -DNDEBUG") # 优化编译

set(SOURCE src/main.cpp)

add_compile_definitions(UNICODE=1) # 启用unicode

add_executable(${PROJECT_NAME} WIN32 ${SOURCE})