
cmake_minimum_required(VERSION 3.1)
project(Scronibox3D)
set(CMAKE_CXX_STANDARD 11)

find_package(OpenGL REQUIRED)
find_package(GLEW REQUIRED)
find_package(glfw3 REQUIRED)

add_executable(Scronibox3D main.cpp)
target_link_libraries(Scronibox3D OpenGL::GL GLEW::GLEW glfw)
