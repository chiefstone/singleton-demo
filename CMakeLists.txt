cmake_minimum_required (VERSION 2.6)
project(loggerdemo)
set(CMAKE_CXX_FLAGS
  "-O2 -std=c++11")
set(HEADER_FILES
  lazylogger.hpp)
add_executable(loggerdemo
	lazylogger.cpp
	main.cpp
)
