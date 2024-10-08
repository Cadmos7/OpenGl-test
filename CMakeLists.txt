cmake_minimum_required(VERSION 3.5.0)
project(OPENGL-TEST VERSION 0.1.0)

add_executable(OPENGL-TEST src/main.cpp)

target_link_libraries(OPENGL-TEST glfw)