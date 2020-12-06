cmake_minimum_required(VERSION 3.12)

add_executable(gol_tests gol_tests.cpp)
target_link_libraries(gol_tests gtest)