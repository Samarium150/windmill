include_directories(${PROJECT_HEADER_DIR})

file(GLOB PROJECT_HEADER_FILES ${PROJECT_HEADER_DIR}/*.h)
#file(GLOB PROJECT_SOURCE_FILES ${PROJECT_SOURCE_DIR}/*.cpp)

add_executable("windmill" "windmill.cpp" ${PROJECT_HEADER_FILES})
