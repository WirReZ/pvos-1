set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -O2")

add_executable(cviko5 cviko5.cpp)
target_link_libraries(cviko5 rt)
