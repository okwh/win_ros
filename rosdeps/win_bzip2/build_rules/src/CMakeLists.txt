
file(GLOB HEADERS RELATIVE ${CMAKE_CURRENT_SOURCE_DIR} *.h)
install(FILES ${HEADERS} DESTINATION include)
