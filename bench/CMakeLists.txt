add_executable(bench bench.cc)
target_link_libraries(bench lalogf benchmark::benchmark)
