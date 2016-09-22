include_directories(${ZLIB_INCLUDE_DIR})
SET( SOURCES
	unzip.c
	${ZLIB_INCLUDE_DIR}/zlib.h
)

ADD_LIBRARY( unzip STATIC ${SOURCES} )

