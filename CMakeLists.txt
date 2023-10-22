cmake_minimum_required(VERSION 3.27)

set(PROJECT_NAME SocketProgramming)


project(${PROJECT_NAME})

file(GLOB SOURCES
	"${PROJECT_SOURCE_DIR}/include/*.h"
	"${PROJECT_SOURCE_DIR}/include/*.hpp"
	"${PROJECT_SOURCE_DIR}/src/*.cpp"
	"${PROJECT_SOURCE_DIR}/src/*.c"
	"main.cpp"
)


add_executable(${PROJECT_NAME} ${SOURCES})

