

cmake_minimum_required(VERSION 3.4 FATAL_ERROR)
project(bioelectrics_monodomain VERSION 0.1.0 LANGUAGES C)
enable_language(Fortran)

find_package(OpenCMISSLibs 1.3.0 REQUIRED COMPONENTS Iron CONFIG)

add_subdirectory(src)

