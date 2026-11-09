if(TARGET app)
  target_sources(app PRIVATE src/behaviors/behavior_rgb_local.c)
endif()

# PMW3610 driver (vendored from badjeff/zmk-pmw3610-driver, with timer polling)
if(CONFIG_PMW3610_ALT)
  add_subdirectory(drivers/pmw3610)
endif()
