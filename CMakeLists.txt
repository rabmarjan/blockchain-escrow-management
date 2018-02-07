cmake_minimum_required(VERSION 3.9)
project(escrow_management)
include_directories(include)

set(CMAKE_CXX_STANDARD 14)
set(SOURCES src/main.cpp src/consumer.cpp src/producer.cpp src/locker.cpp src/ledger.cpp)

add_executable(escrow_management main.cpp)
