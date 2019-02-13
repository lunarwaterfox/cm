add_executable(test_core test.cpp)
target_link_libraries(test_core core gtest_main)

include(GoogleTest)
gtest_discover_tests(test_core)