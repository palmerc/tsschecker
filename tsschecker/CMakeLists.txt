cmake_minimum_required( VERSION 3.8 )

project( tsschecker )

set( SOURCE_FILES
    download.c
    main.c
    tss.c
    tsschecker.c )

add_executable( tsschecker ${SOURCE_FILES} )
target_link_libraries( tsschecker crypto jssy fragmentzip irecovery )
