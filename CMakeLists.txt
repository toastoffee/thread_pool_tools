cmake_minimum_required(VERSION 3.27)
project(thread_pool_tools)

set(CMAKE_CXX_STANDARD 11)

add_executable(thread_pool_tools
        main.cpp
        one_file/thread_pool.hpp
)
