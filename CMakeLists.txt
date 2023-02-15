cmake_minimum_required(VERSION 3.16)
project(test LANGUAGES CXX)

add_subdirectory(lib/raylib)

add_executable(test
    src/main.cpp
)

target_link_libraries(test
    raylib
)
