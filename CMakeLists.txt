
add_library(FlowLayout 
flowlayout.h
flowlayout.cpp
)
target_include_directories(FlowLayout PUBLIC .)
target_link_libraries(FlowLayout PRIVATE
    Qt6::Core
    Qt6::Gui
    Qt6::Widgets
)