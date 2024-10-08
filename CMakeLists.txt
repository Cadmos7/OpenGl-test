cmake_minimum_required(VERSION 3.5.0)
project(my_project VERSION 0.1.0)

add_executable(my_project src/main.cpp)

target_link_libraries(my_project glfw)