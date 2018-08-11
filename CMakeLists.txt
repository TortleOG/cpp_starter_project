cmake_minimum_required(VERSION 3.5)

project(intro)

add_executable(intro main.cpp)

if (MSVC)
  target_compile_options(intro PRIVATE /W4)
elseif()
  target_compile_options(intro PRIVATE -W -Wall -Wextra -Wpedantic)
endif()
