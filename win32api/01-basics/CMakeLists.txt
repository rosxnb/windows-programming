add_executable(hello-message WIN32
    hello_world.c
)
target_link_libraries(hello-message PRIVATE user32.lib)


