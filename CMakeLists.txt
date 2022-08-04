project(FinTrack)
cmake_minimum_required(VERSION 3.22)

# C/C++ Standards
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

IF (WIN32)
    message("===== BUILDING FOR WINDOWS =====")
ENDIF (WIN32)

IF (UNIX)
    message("===== BUILDING FOR UNIX" ${UNIX} " =====")
ENDIF (UNIX)


add_subdirectory(module/objects)