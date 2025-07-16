# CMakeList.txt : CMake project for C code, include source and define
# project specific logic here.
#

# Add source to this project's executable.
add_executable (CMakeTarget "helloworld.c")
 

if (CMAKE_VERSION VERSION_GREATER 3.8)
  set_property(TARGET CMakeTarget PROPERTY C_STANDARD 99)
endif()

# TODO: Add tests and install targets if needed.
