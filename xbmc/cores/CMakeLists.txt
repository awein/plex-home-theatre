add_subdirectory(DllLoader)
add_subdirectory(ExternalPlayer)
add_subdirectory(dvdplayer)
add_subdirectory(paplayer)
add_subdirectory(omxplayer)
add_subdirectory(playercorefactory)
add_subdirectory(VideoRenderers)
add_subdirectory(AudioEngine)

find_all_sources(. core_SRCS)
add_sources(${core_SRCS})
