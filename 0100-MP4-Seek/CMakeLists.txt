cmake_minimum_required(VERSION 2.8)

project( Mp4Seek )

find_package( OpenCV REQUIRED )

include_directories( ${OpenCV_INCLUDE_DIRS} )

add_executable( Mp4Seek Mp4Seek.cpp )

target_link_libraries( Mp4Seek ${OpenCV_LIBS} )