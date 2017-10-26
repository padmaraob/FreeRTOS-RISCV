# FreeRTOS port to RISC-V 

This is based on https://github.com/metempsy/FreeRTOS-RISCV with minor fixes and improvements.

The fixes allow this code to run nicely in a Rocket RISC-V processor with a local interrupt controller (Clint) using preemption.

Tested in Spike with several builds including single-task, multi-task and typical demo test including queues, semaphores, mutexes and about a dozen concurrent tasks.

Tools used

Spike commit on 20th October, 2017 "3b1e9ab7522b3b20cde6bd8d9f2b28222463cf1b"

riscv64-unknown-elf-gcc (GCC) version 7.1.1 20170509

