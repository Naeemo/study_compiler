cmake_minimum_required(VERSION 3.16)
project(c_debug C)

set(CMAKE_C_STANDARD 11)

add_executable(c_debug chapter1/sumc.c chapter2/lexical_analyzer_for_if_and_c_vars.c)