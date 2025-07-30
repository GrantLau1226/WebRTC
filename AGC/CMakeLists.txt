# cmake_minimum_required(VERSION 3.9)
# project(agc)

# add_executable(agc main.c agc.c)

PROJECT(agc)
CMAKE_MINIMUM_REQUIRED(VERSION 2.6)
AUX_SOURCE_DIRECTORY(. DIR_SRCS)
ADD_EXECUTABLE(main ${DIR_SRCS})
