cmake_minimum_required(VERSION 4.0)
project(Lp
        CXX)
add_library(Lp
            "${PROJECT_SOURCE_DIR}/include/Lp/UI/TextSetter.hpp"
            "${PROJECT_SOURCE_DIR}/src/Lp/UI/TextSetter.cpp")
target_include_directories(Lp PUBLIC
                           "${PROJECT_SOURCE_DIR}/include")
