
add_executable(random random.cpp)

target_include_directories(random PRIVATE ../lazperf)
lazperf_target_compile_settings(random)
target_link_libraries(random PRIVATE ${LAZPERF_STATIC_LIB})

