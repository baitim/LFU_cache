cmake_minimum_required(VERSION 3.11)
project(caches)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

if(NOT CMAKE_BUILD_TYPE)
    set(CMAKE_BUILD_TYPE Release)
endif()

enable_testing()

set(CMAKE_CXX_FLAGS_DEBUG "-Wall -g -O0 -fsanitize=address -fsanitize=undefined")

add_subdirectory(./src)