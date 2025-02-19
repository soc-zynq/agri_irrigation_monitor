# Create a library called "agri_irrigation_monitor"
add_library(agri_irrigation_monitor_lib agri_irrigation_monitor.cpp)

# Specify include directories for the library
target_include_directories(agri_irrigation_monitor_lib PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/../../include)
