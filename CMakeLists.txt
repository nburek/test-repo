cmake_minimum_required(VERSION 3.0.2)
project(test_package)

SET(TEST_PACKAGE_VERSION 1.0.0)

message("Hello testing")

add_compile_options(-std=c++11)
install(
  DIRECTORY include/
  DESTINATION include/
)

