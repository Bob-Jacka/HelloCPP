cmake_minimum_required(VERSION 3.10)

# Укажите имя проекта
project(HelloWorld)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)

add_executable(HelloWorld main.cpp)
