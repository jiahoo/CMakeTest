project(HELLO)
add_subdirectory(src bin)
install(FILES COPYRIGHT README DESTINATION share/doc/cmake/)
install(PROGRAMS runhello.sh DESTINATION bin)
install(DIRECTORY doc/ DESTINATION share/doc/cmake)

