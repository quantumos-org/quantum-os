cmake_minimum_required(VERSION 3.5...3.19)

if (${CMAKE_VERSION} VERSION_LESS 3.12)
    cmake_policy(VERSION ${CMAKE_VERSION})
endif()

project(quantum_os_exec LANGUAGES C)

add_executable(quantum_os_exec main.c)
