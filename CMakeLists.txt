PROJECT(Wingman)
cmake_minimum_required(VERSION 3.1.2)

set(CMAKE_CXX_STANDARD 11)

include(${CMAKE_BINARY_DIR}/conanbuildinfo.cmake)
conan_basic_setup(TARGETS)
INCLUDE("${Wingman_SOURCE_DIR}/cmake_conf/Wingman.cmake")

ADD_SUBDIRECTORY("Wingman")

