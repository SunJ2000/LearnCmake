INCLUDE_DIRECTORIES(../lib)
ADD_EXECUTABLE(hello main.cpp)
TARGET_LINK_LIBRARIES(hello HELLOLIB) 

 




MESSAGE("CMAKE_BINARY_DIR: " ${CMAKE_BINARY_DIR})
MESSAGE("CMAKE_SOURCE_DIR: " ${CMAKE_SOURCE_DIR})
MESSAGE("CMAKE_CURRENT_SOURCE_DIR: " ${CMAKE_CURRENT_SOURCE_DIR})
MESSAGE("CMAKE_CURRRENT_BINARY_DIR: " ${CMAKE_CURRRENT_BINARY_DIR})
MESSAGE("CMAKE_CURRENT_LIST_FILE: " ${CMAKE_CURRENT_LIST_FILE})
MESSAGE("CMAKE_CURRENT_LIST_LINE: " ${CMAKE_CURRENT_LIST_LINE})
MESSAGE("EXECUTABLE_OUTPUT_PATH: " ${EXECUTABLE_OUTPUT_PATH})

# CMAKE_BINARY_DIR: /home/sunj200/C++/LearnCmake/t2/build
# CMAKE_SOURCE_DIR: /home/sunj200/C++/LearnCmake/t2
# CMAKE_CURRENT_SOURCE_DIR: /home/sunj200/C++/LearnCmake/t2/src
# CMAKE_CURRRENT_BINARY_DIR: 
# CMAKE_CURRENT_LIST_FILE: /home/sunj200/C++/LearnCmake/t2/src/CMakeLists.txt
# CMAKE_CURRENT_LIST_LINE: 15
# EXECUTABLE_OUTPUT_PATH: 

