cmake_minimum_required( VERSION 3.14 )

project( fugio-portaudio-api LANGUAGES CXX )

install( DIRECTORY ${CMAKE_SOURCE_DIR}/fugio-portaudio/include/fugio DESTINATION . COMPONENT ${PROJECT_NAME} )

set( CPACK_ARCHIVE_FUGIO-PORTAUDIO-API_FILE_NAME "fugio-portaudio-api" PARENT_SCOPE )

