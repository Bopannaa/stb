cmake_minimum_required(VERSION 3.16)

project(stb_image
        VERSION 1.0.0
        DESCRIPTION "stb image library")

set(HDRS 
    ${CMAKE_CURRENT_SOURCE_DIR}/stb_image.h)

set(SRCS
    ${CMAKE_CURRENT_SOURCE_DIR}/stb_image.cpp)

add_library(${PROJECT_NAME} STATIC ${HDRS} ${SRCS})