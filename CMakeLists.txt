cmake_minimum_required(VERSION 3.20)

project(f7f6
  VERSION
    1.0
  DESCRIPTION
    "A minimal text editor"
  LANGUAGES
    CXX
)

set(CMAKE_CXX_STANDARD 20)

add_executable(f7 src/main.cpp)
