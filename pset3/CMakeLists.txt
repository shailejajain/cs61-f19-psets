cmake_minimum_required(VERSION 3.13)
project(pset3)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(pset3
        build/mkbootdisk.cc
        build/mkchickadeesymtab.cc
        build/qemu-nograb.c
        boot.cc
        elf.h
        k-apic.hh
        k-hardware.cc
        k-memviewer.cc
        k-pci.hh
        k-vmiter.cc
        k-vmiter.hh
        kernel.cc
        kernel.hh
        lib.cc
        lib.hh
        p-allocator.cc
        p-fork.cc
        p-forkexit.cc
        types.h
        u-lib.cc
        u-lib.hh
        x86-64.h)
