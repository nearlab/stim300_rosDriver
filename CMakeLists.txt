cmake_minimum_required(VERSION 3.12)
project(stim300)

set(CMAKE_CXX_STANDARD 14)

include_directories(include)
file(GLOB SOURCES "src/*.cpp" "src/*/*.cpp")
add_executable(stim300 ${SOURCES})