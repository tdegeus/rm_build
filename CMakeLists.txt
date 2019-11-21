
cmake_minimum_required(VERSION 3.0)

project(rm_build)

set(PROJECT_BINARIES "rm_build")

INSTALL(PROGRAMS ${CMAKE_CURRENT_SOURCE_DIR}/${PROJECT_BINARIES} DESTINATION bin)
