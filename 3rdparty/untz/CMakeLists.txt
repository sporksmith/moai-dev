find_package(ALSA REQUIRED)

include_directories(
    include
    src
    src/native/linux
    ../rtaudio-4.0.11
    ../rtaudio-4.0.11/include
    ${ALSA_INCLUDE_DIRS}
)

add_definitions(-D__LINUX_PULSE__ -D__LINUX_ALSA__ -D__LINUX_OSS__)

add_library(untz STATIC
    include/Untz.h
    include/UntzSystem.h
    include/UntzSound.h
    src/UserAudioSource.h
    src/BufferedAudioSourceThread.h
    src/native/linux/WaveFile.h
    src/native/linux/RiffFile.h
    src/native/linux/WaveFileAudioSource.h
    src/SoundData.h
    src/RAudioBuffer.h
    src/threading/RCriticalSection.h
    src/threading/Threading.h
    src/threading/RScopedLock.h
    src/threading/RThread.h
    src/threading/RSyncEvent.h
    src/AudioSource.h
    src/MemoryAudioSource.h
    src/counted_ptr.h
    src/BufferedAudioSource.h
    src/AudioMixer.h
    src/SystemData.h
    src/OggAudioSource.h
    src/BufferedAudioSourceThread.cpp
    src/OggAudioSource.cpp
    src/native/linux/WaveFileAudioSource.cpp
    src/native/linux/RiffFile.cpp
    src/native/linux/UntzSystem.cpp
    src/native/linux/WaveFile.cpp
    src/UserAudioSource.cpp
    src/AudioMixer.cpp
    src/UntzSound.cpp
    src/MemoryAudioSource.cpp
    src/BufferedAudioSource.cpp

    ../rtaudio-4.0.11/RtAudio.cpp
    ../rtaudio-4.0.11/RtAudio.h
    ../rtaudio-4.0.11/RtError.h
    ../rtaudio-4.0.11/include/soundcard.h
)

target_link_libraries(untz
    ${ALSA_LIBRARIES}
    pulse-simple
    vorbisfile
)
