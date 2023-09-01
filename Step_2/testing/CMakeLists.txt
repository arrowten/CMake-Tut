cmake_minimum_required(VERSION 3.14)

project(example)

add_executable(${CMAKE_PROJECT_NAME} sample.cpp)

target_link_directories(${CMAKE_PROJECT_NAME} PRIVATE ../lib/)

target_link_libraries(${CMAKE_PROJECT_NAME} mathe)
