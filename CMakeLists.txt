cmake_minimum_required (VERSION 3.0)
project (shell)

if (CMAKE_COMPILER_IS_GNUCXX)
	set(CMAKE_CXX_FLAGS " -std=c++11 -O0 -g3 -Wall -Wextra ${CMAKE_CXX_FLAGS}")
endif()

add_executable(shell

	
	shell.cpp
)