add_library(aku STATIC
    AKU.cpp
    AKU.h
    AKU-untz.cpp
    AKU.h
)

target_link_libraries(aku
    zlcore
    moaicore
    moaiext-untz
    uslscore
)
