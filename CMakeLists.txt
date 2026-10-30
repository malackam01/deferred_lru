cmake_minimum_required(VERSION 3.10)
project(deferred_lru)

add_library(deferred_lru INTERFACE)
target_include_directories(deferred_lru INTERFACE include)
add_subdirectory(benchmark)
