add_library(zlcore STATIC
    ZLFileSystem.cpp
    zl_vfscanf.cpp
    zl_replace_new_delete.h
    ZLFile.h
    zl_util.cpp
    ZLFileSystem.h
    zl_mutex.cpp
    ZLZipStream.h
    ZLZipArchive.h
    ZLDirectoryItr.cpp
    pch.h
    ZLZipArchive.cpp
    ZLZipStream.cpp
    zl_replace_locale.h
    zl_replace_stdlib.h
    zl_util.h
    zlcore-pch.cpp
    ZLVirtualPath.cpp
    zlcore.h
    CMakeLists.txt
    zl_mutex.h
    zl_replace_stdio.h
    zlcore.cpp
    ZLFile.cpp
    ZLDirectoryItr.h
    ZLVirtualPath.h
    zl_replace.h
)

target_link_libraries(zlcore
    tlsf
)

