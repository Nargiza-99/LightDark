cmake_minimum_required(VERSION 2.8)
project(LightDark)
set(OpenCV_DIR C:/opencv/build)
find_package( OpenCV REQUIRED )
include_directories( ${OpenCV_INCLUDE_DIRS} )
add_executable( LightDark LightDark.cpp)
target_link_libraries( LightDark ${OpenCV_LIBS} )