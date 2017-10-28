cmake_minimum_required(VERSION 2.8)
add_library(fast_akaze STATIC
    akaze.cpp
    AKAZEFeatures.cpp
    fed.cpp
    nldiffusion_functions.cpp
)

INSTALL(TARGETS fast_akaze DESTINATION lib/)
