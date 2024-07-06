cmake_minimum_required(VERSION 3.22.0)
project(stb)

add_library(stb stb_image.h stb_image.c)
target_include_directories(stb PUBLIC ./)