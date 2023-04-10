cmake_minimum_required(VERSION 3.23)
project(OOP2023 C)

set(CMAKE_C_STANDARD 99)

add_executable(OOP2023 main.c)
add_subdirectory(libs)
target_link_libraries(OOP2023 algorithms)
target_link_libraries(OOP2023 datastructures)