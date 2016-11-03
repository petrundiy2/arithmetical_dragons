cmake_minimum_required(VERSION 2.8)

project(arithmetical_dragons-master)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES arithmetical_dragons.cpp hero.h dragon.h unit.h)
add_executable(arithmetical_dragons-master ${SOURCE_FILES})

