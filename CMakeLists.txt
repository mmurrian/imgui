add_library(imgui SHARED
    imgui_demo.cpp imgui_draw.cpp imgui_internal.h imgui_tables.cpp imgui_widgets.cpp imgui.cpp imgui.h)
target_include_directories(imgui PUBLIC .)

add_subdirectory(backends)