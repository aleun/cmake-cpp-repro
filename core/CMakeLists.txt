set(TARGET core)
set(SOURCES foo.c)
add_library(${TARGET} OBJECT ${SOURCES})
target_include_directories(${TARGET} PUBLIC .)

