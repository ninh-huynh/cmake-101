cmake_minimum_required(VERSION 3.0.0)
project(directory_test)

include_directories(include)

# set(SOURCES src/main.cpp src/Student.cpp)
file(GLOB SOURCES "src/*.cpp")

add_executable(testStudent ${SOURCES})