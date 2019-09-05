cmake_minimum_required(VERSION 3.14)
project(VM45AbstractMachineTest1_C__)

set(CMAKE_CXX_STANDARD 17)

add_executable(VM45AbstractMachineTest1_C__ main.cpp VM45/VM.cpp VM45/VM.h VM45/Register.cpp VM45/Register.h)