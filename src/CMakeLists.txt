cmake_minimum_required(VERSION 3.13)

project(MPAGSCipher VERSION 0.2.0)

set(CMAKE_VERBOSE_MAKEFILE ON)
set(CMAKE_CXX_EXTENSIONS OFF)

set(CMAKE_CXX_FLAGS "-Wall -Wextra -Wshadow -pedantic")

add_executable(mpags-cipher mpags-cipher.cpp)
target_compile_features(mpags-cipher PRIVATE cxx_std_11)