cmake_minimum_required(VERSION 3.10)
project(VardenisPavardenis)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Sukuriam executable iš visų src failų
add_executable(programa
    src/main.cpp
    src/funkcijos.cpp
    src/studentas.cpp
    src/sum.cpp
)
