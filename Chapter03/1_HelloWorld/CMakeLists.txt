# 0.) Create code and CMake File
# 1.) mkdir build
# 2.) cd build
# 3.) cmake .. - Build files generaterd (for example Makefiles)
# 4a.) cmake --build . (Compile all targets)
# 4b.) make
# 5.) ./Executable

cmake_minimum_required(VERSION 3.22)

project(
  CppProjectTemplate
  VERSION 1.0.0
  LANGUAGES C CXX)

add_executable(Executable main.cc)
