cmake_minimum_required(VERSION 3.2...3.27.5)
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

project(cmake_prj)

enable_testing()
add_subdirectory(lib/googletest)

add_subdirectory(obychaika)
add_subdirectory(sort)


set(CMAKE_SUPPRESS_REGENERATION true)


