cmake_minimum_required(VERSION 3.7)
project(CheckoutSystem)

set(CMAKE_CXX_STANDARD 14)

set(SOURCE_FILES main.cpp Shop.cpp Shop.h)
add_executable(CheckoutSystem ${SOURCE_FILES})