cmake_minimum_required(VERSION 3.5)

project(PlainCTest LANGUAGES C)

add_executable(PlainCTest main.c)

install(TARGETS PlainCTest
    LIBRARY DESTINATION ${CMAKE_INSTALL_LIBDIR})
