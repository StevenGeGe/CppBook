cmake_minimum_required(VERSION 3.12)
project(CppBook)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)
include_directories(.idea)
include_directories(cmake-build-debug)

add_executable(CppBook
        .idea/vcs.xml
        .idea/workspace.xml)
