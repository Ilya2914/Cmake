cmake_minimum_required(VERSION 3.2...3.27.5)

project(cmake_prj)

enable_testing()
add_subdirectory(lib/googletest)

add_subdirectory(obychaika)
add_subdirectory(sort)
add_subdirectory(unit_test)


set(CMAKE_SUPPRESS_REGENERATION true)
