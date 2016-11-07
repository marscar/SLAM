cmake_minimum_required(VERSION 2.8.12)

project(RtTracker)

find_package(OpenCV REQUIRED)
include_directories(${OpenCV_INCLUDE_DIRS})

add_executable(rtTracker rtTracker.cpp)
target_link_libraries(rtTracker ${OpenCV_LIBS})

#add_executable(rtTracker2 rtTracker2.cpp)
#target_link_libraries(rtTracker2 ${OpenCV_LIBS})
