cmake_minimum_required(VERSION 3.15)
project(priject-name VERSION 0.0.0 LANGUAGES CXX)

#set(CMAKE_VERBOSE_MAKEFILE on)

list(APPEND CMAKE_MODULE_PATH "${CMAKE_CURRENT_SOURCE_DIR}/cmake")

add_subdirectory(project-name)
add_subdirectory(samples)
add_subdirectory(tests)