set(includedirs src)

set(req arduino )

idf_component_register(
	INCLUDE_DIRS ${includedirs} 
	SRCS ${SOURCES}
	REQUIRES ${req})
