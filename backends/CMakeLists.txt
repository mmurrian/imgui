add_library(imgui_backends SHARED
    imgui_impl_glfw.cpp imgui_impl_glfw.h
    imgui_impl_opengl3.cpp imgui_impl_opengl3.h)
target_include_directories(imgui_backends PUBLIC .)
target_link_libraries(imgui_backends PRIVATE imgui glfw)