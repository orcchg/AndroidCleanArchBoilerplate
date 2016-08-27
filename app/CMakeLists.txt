cmake_minimum_required(VERSION 3.4.1)

set( SOURCES src/main/cpp/native-lib.cpp )
add_library( native-lib SHARED ${SOURCES} )
target_link_libraries( native-lib log )
