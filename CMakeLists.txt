cmake_minimum_required(VERSION 3.12.4)


add_library(SPinGW  serialport.c)
target_include_directories(SPinGW PUBLIC .)
