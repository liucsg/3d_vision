cmake_minimum_required(VERSION 2.8.3)
project(get_transform_pc)
add_definitions(--std=c++11 -Wno-unknown-pragmas -w)
find_package(catkin_simple REQUIRED)
catkin_simple(ALL_DEPS_REQUIRED)
cs_add_executable(get_transform_pc src/main.cpp)
cs_install()
cs_export()
