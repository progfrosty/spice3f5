cmake_minimum_required(VERSION 2.6)
project(Spice3f5)
if (UNIX AND NOT APPLE)
  add_definitions(-Dlinux)
  add_subdirectory(src)
  add_subdirectory(lib)
endif (UNIX)
