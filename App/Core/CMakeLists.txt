cmake_minimum_required(VERSION 3.19)

project(App)

include(../../CMake/CommonMacros.txt)

SETUP_APP(Core "Core")

target_link_libraries(Core PRIVATE SharedUtils assimp meshoptimizer)
