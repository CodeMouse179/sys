cmake_minimum_required(VERSION 3.11)

set(CMAKE_CXX_STANDARD 98)

project(sys)

include_directories(../../)

add_executable(s
    ../../sys.h
    main.cpp
)