cmake_minimum_required(VERSION 3.27)

project(ByteStream)

add_library(${PROJECT_NAME} ByteStream.cpp)
target_include_directories(${PROJECT_NAME} PUBLIC ${PROJECT_SOURCE_DIR})