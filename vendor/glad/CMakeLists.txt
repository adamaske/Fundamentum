add_library(GLAD INTERFACE)#header only

target_include_directories(GLAD INTERFACE ${CMAKE_CURRENT_SOURCE_DIR}/include)
