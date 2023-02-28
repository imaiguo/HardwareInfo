
cmake_minimum_required(VERSION 3.5)

project(HardWareInfo LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

set (SRC_LIST main.cpp InstructionSet.cc)

add_executable(HardWareInfo ${SRC_LIST})

add_executable(CpuId cpuid_linux.cc)
