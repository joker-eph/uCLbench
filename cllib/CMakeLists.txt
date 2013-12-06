add_library(cllib STATIC clinfo.cpp clcommon.cpp)
target_link_libraries(cllib ${OPENCL_LIBRARIES})