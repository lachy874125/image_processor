cmake_minimum_required(VERSION 3.28.3)

project(HelloSDL2)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_C_STANDARD_REQUIRED True)

set(SOURCE_FILES 01_hello_SDL.cpp)

add_executable(${PROJECT_NAME} ${SOURCE_FILES})

target_link_libraries(${PROJECT_NAME} PRIVATE SDL2)