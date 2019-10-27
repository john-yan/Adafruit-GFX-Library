#idf_component_register(SRCS "Adafruit_GFX.cpp" "Adafruit_SPITFT.cpp" "glcdfont.c" INCLUDE_DIRS include)

set(COMPONENT_ADD_INCLUDEDIRS include)
set(COMPONENT_SRCS "Adafruit_GFX.cpp" "Adafruit_SPITFT.cpp" "glcdfont.c")
register_component()
