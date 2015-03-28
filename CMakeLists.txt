cmake_minimum_required (VERSION 2.6)
project(AstyleGoogle)
add_executable(astyle-google 
  ASBeautifier.cpp
  ASEnhancer.cpp
  ASFormatter.cpp
  ASLocalizer.cpp
  ASLocalizer.h
  ASResource.cpp
  CMakeLists.txt
  README.md
  astyle.h
  astyle_main.cpp
  astyle_main.h
)

