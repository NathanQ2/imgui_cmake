cmake_minimum_required(VERSION 3.31)
project(imgui)

set(CMAKE_CXX_STANDARD 23)

file(GLOB_RECURSE IMGUI_SOURCES *.cpp *.h backends/**.cpp backends/**.h)
set(IMGUI_INCLUDE ${CMAKE_CURRENT_SOURCE_DIR} ${CMAKE_CURRENT_SOURCE_DIR}/backends/)

# target_include_directories(${PROJECT_NAME} PUBLIC * backends/)
