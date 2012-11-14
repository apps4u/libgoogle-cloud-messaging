# Grab the sources.
file(GLOB GCM_HEADERS "*.hpp")
file(GLOB GCM_SOURCES "*.cpp")

add_library(libgoogle-cloud-messaging SHARED ${GCM_SOURCES})
