cmake_minimum_required(VERSION 3.10)

# Set the project name
project({{PROJECT_NAME}})

# Add include directories
include_directories(include)

# Add the executable
add_executable({{PROJECT_NAME}} src/main.cpp)