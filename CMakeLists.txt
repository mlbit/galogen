cmake_minimum_required(VERSION 3.8)
project(galogen)
add_executable(galogen galogen.cpp third_party/tinyxml2.cpp)
message("BINARY_DIR ${CMAKE_BINARY_DIR}")
install(TARGETS galogen 
		RUNTIME DESTINATION /opt)