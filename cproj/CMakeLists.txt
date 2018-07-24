CMAKE_MINIMUM_REQUIRED(VERSION 3.8)

# Set the project name.
PROJECT (cpp_git)
# Preprocessor definitions
ADD_DEFINITIONS(-DUNICODE -D_UNICODE )
# Set the include directories.
INCLUDE_DIRECTORIES(.)
# Set the output type for this project.
# This shall be an executable
ADD_EXECUTABLE(cpp_git "./main.cpp")
