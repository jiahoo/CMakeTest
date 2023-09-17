
include_directories(/usr/include/hello)
add_executable(hello main.cpp)
target_link_libraries(hello libhello.a)
