include_directories(include)
link_directories(lib)
link_libraries(fltk)

add_executable( ${PROJECT_NAME} main.cpp )
target_link_libraries(${PROJECT_NAME} comctl32 fltk)