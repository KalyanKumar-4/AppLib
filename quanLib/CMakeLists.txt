cmake_minimum_required(VERSION 3.2)

add_library(quanLib src/Calc.cpp)
message("${CMAKE_CURRENT_SOURCE_DIR} is the current source")
 

target_include_directories( quanLib PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/include)
