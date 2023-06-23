cmake_minimum_required(VERSION 3.10)
project(clox)

set(CMAKE_C_STANDARD 99)

add_executable(clox scanner.c table.c object.c memory.c vm.c debug.c main.c chunk.c compiler.c value.c)
