project( Mcr )

file( GLOB headers *.h )
file( GLOB sources *.cpp )

add_library( ${PROJECT_NAME} "${headers}" "${sources}" )
