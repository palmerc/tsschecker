cmake_minimum_required( VERSION 3.8 )

set( LIBRESSL_APPS off )
set( LIBRESSL_TESTS off )
set( LIBRESSL_SKIP_INSTALL on )

add_subdirectory( tsschecker )
add_subdirectory( external/jssy )
add_subdirectory( external/libressl )
add_subdirectory( external/libfragmentzip )
add_subdirectory( external/libirecovery )
