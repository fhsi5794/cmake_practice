cmake_minimum_required(VERSION 3.10)

# set the project name
project(ex1)

# set variable
set(SRC_LIST main.c hello.c)

# add the executable
add_executable(ex1 ${SRC_LIST})