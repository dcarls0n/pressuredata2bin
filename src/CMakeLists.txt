#Require Ver 3.6 for Intel compiler support
cmake_minimum_required(VERSION 3.6)
project(autocorrelate_threads LANGUAGES CXX)

project(pdatatxt2bin C CXX)

add_executable(pdatatxt2bin pdatatxt2bin.cpp)

set_target_properties(pdatatxt2bin PROPERTIES
	CXX_STANDARD 14
	CXX_EXTENSIONS FALSE
	CXX_STANDARD_REQUIRED TRUE
)

set(CMAKE_CXX_STANDARD 14)