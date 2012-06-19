add_library(moaiext-untz STATIC
    MOAIUntzSystem.h
    MOAIUntzSystem.cpp
    MOAIUntzSound.h
    MOAIUntzSound.cpp
    MOAIUntzSampleBuffer.h
    MOAIUntzSampleBuffer.cpp
)

target_link_libraries(moaiext-untz
    untz
)
