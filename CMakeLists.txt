cmake_minimum_required(VERSION 3.12)
project(OOP-Labs)

set(CMAKE_CXX_STANDARD 17)

add_subdirectory("${PROJECT_SOURCE_DIR}/lib")
enable_testing()

add_subdirectory(lw1/replace)
add_subdirectory(lw3/car)
