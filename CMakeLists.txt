cmake_minimum_required(VERSION 3.20)

add_subdirectory(lib)

add_executable(template
  src/main.cpp
)

target_link_libraries(template
  PRIVATE
    raylib
)