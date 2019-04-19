cmake_minimum_required(VERSION 2.8.9)
project(crakwech)

include_directories(include)

set(SRC src/main.c )

add_executable(crakwech ${SRC})

FIND_PACKAGE(PkgConfig REQUIRED)

