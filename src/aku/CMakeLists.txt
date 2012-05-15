add_library(aku STATIC
    AKU.cpp
    AKU.h
)

target_link_libraries(aku
    zlcore
    moaicore
    uslscore
)
