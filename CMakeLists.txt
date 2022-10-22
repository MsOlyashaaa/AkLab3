cmake_minimum_required(VERSION 3.22)	 

project(labwork)			

add_library(factorial STATIC factorial.cpp)	

add_executable(main main.cpp)

target_link_libraries(main factorial)