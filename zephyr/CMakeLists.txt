if(CONFIG_JSMN_LIB)
  zephyr_library_named(jsmn)
  zephyr_include_directories(
    ./
  )

  zephyr_library_sources(code.c)
endif()
