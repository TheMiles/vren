cmake_minimum_required(VERSION 3.10)
project(vren)

set( 
    ${PROJECT_NAME}_HEADERS 
)

set( 
    ${PROJECT_NAME}_SOURCES
    main.cpp
)

add_executable( ${PROJECT_NAME} ${${PROJECT_NAME}_SOURCES} ${${PROJECT_NAME}_HEADERS} )



