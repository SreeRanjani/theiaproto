cmake_minimum_required(VERSION "3.23.0")

project("HelloWorld")

add_executable("${PROJECT_NAME}" "Main.cpp")

install(TARGETS "${PROJECT_NAME}" DESTINATION bin) 	#${CMAKE_INSTALL_PREFIX}/bin

install(FILES "Main.cpp" DESTINATION src)			#${CMAKE_INSTALL_PREFIX}/bin

