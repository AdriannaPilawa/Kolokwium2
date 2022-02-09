cmake_minimum_required(VERSION 3.10)

project(NAZWA_PROJEKTU)

set(SRC libtest.cpp Student.cpp) 

add_executable(NAZWA_PROJEKTU ${SRC})
add_library(NAZWA_PROJEKTU ${SRC})

install(TARGETS NAZWA_PROJEKTU DESTINATION ./bin)
