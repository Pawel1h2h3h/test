cmake_minimum_required(VERSION 3.10)
project(Przyklad)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Dodajemy moduł src (math_utils + main)
add_subdirectory(src)

# Włączamy testy i dodajemy moduł tests
enable_testing()
add_subdirectory(tests)