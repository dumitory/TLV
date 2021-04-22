cmake_minimum_required(VERSION 3.10)
project(TLVLib VERSION 1.0.0 LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_VERBOSE_MAKEFILE ON)
set(NAME_EXE tlv)

add_executable(${NAME_EXE} src/main.cpp)


