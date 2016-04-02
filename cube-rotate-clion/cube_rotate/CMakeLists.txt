project(cube_rotate)

add_executable(cube_rotate cube.cpp)

target_link_libraries(cube_rotate ${OPENGL_LIBRARIES} ${GLUT_LIBRARY} )
