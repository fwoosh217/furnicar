cmake_minimum_required(VERSION 3.20)


project(furnicar)

add_subdirectory("external/raylib")

add_executable(furnicar "src/main.c")
target_link_libraries(furnicar raylib)