cmake_minimum_required(VERSION 3.12)

project(nativeipc)

add_subdirectory(libuv)
add_subdirectory(libnativeipc)

if(BUILD_TESTING)
  add_subdirectory(tests)
endif()
