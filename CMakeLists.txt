cmake_minimum_required(VERSION 3.0)

project(termboxlib)

add_library(tblib
  src/utf8.c
  src/termbox.c
  )

target_include_directories(tblib
  PUBLIC src/
  )
