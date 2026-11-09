# Vendored from badjeff/zmk-pmw3610-driver (branch zmk-0.4) with timer polling added.
zephyr_library()
zephyr_library_sources(src/pmw3610.c)
zephyr_include_directories(${APPLICATION_SOURCE_DIR}/include)
