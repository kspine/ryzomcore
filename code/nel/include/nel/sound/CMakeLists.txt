FILE(GLOB HEADERS *.h)
ADD_SUBDIRECTORY(driver)
INSTALL(FILES ${HEADERS} DESTINATION include/nel/sound COMPONENT headers)
