cmake_minimum_required(VERSION 3.21)
project(CppScrapShell)

set(CMAKE_CXX_STANDARD 14)

include_directories(src)

add_executable(CppScrapShell
        src/scanner.cpp
        src/scanner.h
        src/token.cpp
        src/token.h
        CppScrapShell.cpp)
