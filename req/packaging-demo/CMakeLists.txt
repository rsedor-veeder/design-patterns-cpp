cmake_minimum_required(VERSION 3.12)
project(packaging-demo)

set(CMAKE_CXX_STANDARD 17)

include_directories(src)
include_directories(include)
file(GLOB_RECURSE MYSOURCES src/*.cpp)

add_executable(packaging-demo ${MYSOURCES})