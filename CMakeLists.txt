project(GoogleCloudMessagingCPlusPlus)
cmake_minimum_required(VERSION 2.8)

# Load up our CMake magic.
add_subdirectory(cmake)

# Set up dependencies.
find(Qt4 COMPONENTS Qt4Network Qt4Core Qt4Test)
find(QJson)

# Grab the subdirectories.
add_subdirectory(src)
