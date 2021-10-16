cmake_minimum_required(VERSION 3.10)
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

project(sfmlgame)
add_executable(sfmlgame main.cpp)
target_include_directories(sfmlgame PUBLIC /usr/include/SFML)
target_link_libraries(sfmlgame sfml-system sfml-window sfml-graphics)
