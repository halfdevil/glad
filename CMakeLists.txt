cmake_minimum_required(VERSION 3.8)

project(glad)

include_directories(include)
add_library(glad src/gl.c)

set_property(TARGET glad PROPERTY FOLDER "ThirdParty")