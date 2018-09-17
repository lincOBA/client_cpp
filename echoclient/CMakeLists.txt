cmake_minimum_required (VERSION 2.6)
add_subdirectory(lib)
add_executable(Flypy src/main.c)
target_link_libraries(Flypy Lib) 
