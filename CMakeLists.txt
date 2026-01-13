cmake_minimum_required(VERSION 3.10)
project(mpi-raytracing)

set(CMAKE_CXX_STANDARD 17)

if(MSVC)
  add_compile_options(/MP)
endif()

add_executable(mpi-raytracing src/main.cpp)
