cmake_minimum_required(VERSION 3.8 FATAL_ERROR)
project(cuda-with-cmake LANGUAGES CUDA)

file(GLOB cuda_source_files "${CMAKE_SOURCE_DIR}/*.cu")

add_executable(vectoradd ${cuda_source_files})