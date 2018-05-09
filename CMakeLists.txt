cmake_minimum_required(VERSION 3.9)
project(trace_generator)

set(CMAKE_CXX_STANDARD 11)

add_executable(trace_generator
        db_parser.cc
        db_parser.h
        dlist.cc
        dlist.h
        FilterList.cc
        FilterList.h
        flist.cc
        flist.h
        hlist.cc
        hlist.h
        stdinc.h
        trace_generator.cc
        trace_tools.cc
        trace_tools.h)
