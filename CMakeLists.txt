CMAKE_MINIMUM_REQUIRED(VERSION 2.4)
cmake_policy(SET CMP0003 NEW)

set(CMAKE_VERBOSE_MAKEFILE false)

get_filename_component(CUEFILE_LIBRARY "libcuefile/src/libcuefile.a" ABSOLUTE)
get_filename_component(REPLAY_GAIN_LIBRARY "libreplaygain/src/libreplaygain.a" ABSOLUTE)

add_subdirectory(libcuefile)
add_subdirectory(libreplaygain)
add_subdirectory(libmpc)
