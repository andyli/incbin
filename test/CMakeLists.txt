cmake_minimum_required(VERSION 3.0)
project(incbinTest C)

include_directories(
    ${CMAKE_CURRENT_SOURCE_DIR}
)

add_executable(asserts
    resources.c
    asserts.c
)
