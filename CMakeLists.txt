cmake_minimum_required(VERSION 3.16)
project(Set)

set(CMAKE_CXX_STANDARD 14)

add_executable(Set main.cpp BinaryTree.hpp BinaryHeap.hpp Interface.cpp Interface.hpp InterfaceBinaryTree.cpp InterfaceBinaryTree.hpp InterfaceBinaryHeap.cpp InterfaceBinaryHeap.hpp tests.hpp)