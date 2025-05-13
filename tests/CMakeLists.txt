add_executable(test_math test_math.cpp)
target_link_libraries(test_math PRIVATE math_utils)
add_test(NAME MathTest COMMAND test_math)