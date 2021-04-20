# The following lines of boilerplate have to be in your project's
# CMakeLists in this exact order for cmake to work correctly
cmake_minimum_required(VERSION 3.5)
list(APPEND EXTRA_COMPONENT_DIRS "components/cryptoauthlib")
include($ENV{IDF_PATH}/tools/cmake/project.cmake)
project(ECC608-Simple-Conn-Test-idf42)