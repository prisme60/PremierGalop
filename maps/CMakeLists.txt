project(MAPSRESOURCES)

install(DIRECTORY "${CMAKE_CURRENT_SOURCE_DIR}" DESTINATION "." COMPONENT "resource" FILES_MATCHING PATTERN "*.map")
