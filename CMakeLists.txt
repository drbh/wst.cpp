#
# wavelet-scatter
cmake_minimum_required (VERSION 3.0)
project(wavelet-scatter VERSION 0.1.0)

set(CMAKE_C_STANDARD   11)
set(CMAKE_CXX_STANDARD 11)

set(TEST_TARGET wavelet-scatter)
add_executable(${TEST_TARGET} src/main.cpp)
