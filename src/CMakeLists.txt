cmake_minimum_required(VERSION 3.6)
project(CMakeHello)

# GLOB searches for files within the current directory matching the 
# specified expression, and assigns the results to a variable.
file(GLOB SOURCES *.c *.h)

add_executable(CMakeHello ${SOURCES})