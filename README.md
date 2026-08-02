# nand2tetris — Building a Computer from the Ground Up

This repo documents my progress through the [nand2tetris](https://www.nand2tetris.org/) course, 
where the goal is to build a complete computer system — starting from a single NAND gate and 
working up through logic gates, an ALU, memory, a CPU, an assembler, and eventually a compiler 
and operating system.

I'm doing this project as part of my path toward RTL and digital chip design. Understanding how 
hardware is built from first principles — rather than just treating a CPU as a black box — is 
foundational to designing it well.

## Why this project

I'm currently studying Computer Science at UT Dallas, with plans to move into Electrical & 
Computer Engineering, and a long-term goal of working as an RTL/chip design engineer. Nand2tetris 
was my starting point because it strips digital design down to its rawest form: pure logic and 
structure, no black boxes.

## Progress

- [x] **Project 1 — Boolean Logic**: Built fundamental logic gates (And, Or, Not, Xor, Mux, DMux) 
  and their multi-bit/multi-way variants (And16, Mux4Way16, DMux8Way, etc.) entirely from NAND gates.
- [x] **Project 2 — Boolean Arithmetic**: Half-adder, full-adder, and a 16-bit ALU *(in progress)*
- [ ] **Project 3 — Sequential Logic**: Flip-flops, registers, RAM, and a Program Counter
- [ ] **Project 4 — Machine Language**: Assembly programming for the Hack platform
- [ ] **Project 5 — Computer Architecture**: Building the full CPU and connecting memory + I/O
- [ ] **Project 6 — Assembler**
- [ ] **Project 7-8 — VM Translator**
- [ ] **Project 9-12 — High-Level Language & Compiler**

## Structure

Each project lives in its own folder (`project01/`, `project02/`, ...) containing:
- `.hdl` files — my hardware implementations, written in the HDL (Hardware Description Language) 
  used by the nand2tetris toolchain
- `.tst` files — provided test scripts used to verify correctness
- `.cmp` files — expected output used by the test scripts to check my implementations

## Tools

- [nand2tetris Software Suite](https://www.nand2tetris.org/software) — the official simulator/tools 
  used to build and test the HDL chips
- VS Code for editing

## What's next

After finishing the full nand2tetris course, I plan to move into SystemVerilog and start working 
with FPGA-based projects and open-source RISC-V cores to build toward real RTL design workflows.
