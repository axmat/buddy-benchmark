add_library(Container Container.cpp)
add_library(PNGImage PNGImage.cpp)

target_link_libraries(PNGImage ${PNG_LIBRARIES})
