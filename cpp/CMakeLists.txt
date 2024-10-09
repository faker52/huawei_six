set(CMAKE_EXE_LINKER_FLAGS "-static-libgcc -static-libstdc++")
cmake_minimum_required(VERSION 3.28)
project(cpp)

set(CMAKE_CXX_STANDARD 17)

add_executable(cpp main.cpp
)
