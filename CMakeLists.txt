cmake_minimum_required(VERSION 3.27)
project(cpc_cpp)

set(CMAKE_CXX_STANDARD 14)

include_directories(bits)

add_executable(cpc_cpp
        main.cpp
        bits/stdc++.h)
