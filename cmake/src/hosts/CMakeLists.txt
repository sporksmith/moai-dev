moai_set_local_source_dir()

add_definitions(-DGLUTHOST_USE_UNTZ)

add_executable(gluthost
    "${local_source_dir}/GlutHost.cpp"
    "${local_source_dir}/GlutHostMain.cpp"
)

target_link_libraries(gluthost
    aku
    moaicore
    utf8
    jansson
    ${OPENGL_LIBRARIES}
    ${GLUT_LIBRARIES}
    GLEW
)

