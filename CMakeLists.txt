cmake_minimum_required(VERSION 3.20)
project(wasmer_test)

set(CMAKE_CXX_STANDARD 11)

include_directories(wasmer/include)
link_directories(wasmer/lib)
link_libraries(wasmer)

add_executable(wasmer_test main.cpp)
