set(MIN_CMAKE_VER "3.20")

cmake_minimum_required(VERSION ${MIN_CMAKE_VER})
project(best)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target x86_64-pc-windows-gnu")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target x86_64-pc-windows-gnu")



include_directories(deps)



add_subdirectory(src)