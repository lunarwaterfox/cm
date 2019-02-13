add_executable(test_core test.cpp)
target_link_libraries(test_core core gtest_main)
add_test(NAME Core COMMAND test_core)