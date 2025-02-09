cmake_minimum_required(VERSION 3.29)
project(windows-programming)

set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_SOURCE_DIR}/targets)
set(CMAKE_LIBRARY_OUTPUT_DIRECTORY ${CMAKE_SOURCE_DIR}/targets)
set(CMAKE_ARCHIVE_OUTPUT_DIRECTORY ${CMAKE_SOURCE_DIR}/targets)
set(CMAKE_PDB_OUTPUT_DIRECTORY     ${CMAKE_SOURCE_DIR}/targets)


add_subdirectory(win32api)
add_subdirectory(mfc)