# CMake for relic keyboard shield

if(SHIELD STREQUAL "relic_left")
  add_overlay(${CMAKE_CURRENT_LIST_DIR}/relic_left.overlay)
endif()

if(SHIELD STREQUAL "relic_right")
  add_overlay(${CMAKE_CURRENT_LIST_DIR}/relic_right.overlay)
endif()
