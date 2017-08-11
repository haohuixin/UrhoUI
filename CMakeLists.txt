file (GLOB_RECURSE SOURCE_FILES *.cpp *.h)
add_library (UrhoUI STATIC ${SOURCE_FILES})
target_link_libraries (UrhoUI Atomic)
target_include_directories(UrhoUI PUBLIC .)
