cmake_minimum_required(VERSION 3.7)
project(codejam)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES horse/horses.cpp)
add_executable(codejam ${SOURCE_FILES})
add_executable(horses horse/horses.cpp)
add_executable(leader leader/leader.cpp)
add_executable(pancake pancake/pancake.cpp)
add_executable(pancake2 pancake/pancake2.cpp)
add_executable(g googlement/g.cpp)
add_executable(test2 test/test2.cpp)
add_executable(gv2 googlement/gv2.cpp)
add_executable(everest everest/everest.cpp)
add_executable(pixels pixels/dijkstra.h pixels/dijkstra.cpp pixels/pixels.cpp )

add_executable(dijkstra pixels/dijkstra.cpp)