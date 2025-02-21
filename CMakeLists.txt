cmake_minimum_required(VERSION 3.10)
project(test_cpp101)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(${PROJECT_NAME} 
    src/test_cpp101.cpp
)

target_link_libraries(${PROJECT_NAME} )

