cmake_minimum_required(VERSION 3.13)

project(lib)

set(library 
    foo.cpp
    foo.h)

add_executable(lib ${library})
