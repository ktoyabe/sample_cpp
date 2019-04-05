cmake_minimum_required(VERSION 3.10)
project(sample_exe)

add_executable(sample_exe src/main.cpp)

include_directories(
        ${sample_lib_SOURCE_DIR}/src
)

target_link_libraries(sample_exe sample_lib)
