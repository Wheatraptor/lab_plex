project(test)

include_directories("${CMAKE_CURRENT_SOURCE_DIR}/../gtest")

add_executable(test test_plex.cpp test_main.cpp)

target_link_libraries(test gtest Plex Line Point Square Circle Canvas)
