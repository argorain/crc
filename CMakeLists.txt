cmake_minimum_required (VERSION 2.8)

project (crc)

set(CMAKE_C_COMPILER "gcc")
set(CMAKE_C_FLAGS "-Wall -pedantic -std=gnu99 -lm -g")

set(HEADER_FILES
       )

set(SOURCE_FILES
        main.c
       )


add_executable(crc main.c ${SOURCE_FILES} ${HEADER_FILES})
