# CMPE 413 Cache Project

## Overview
This project implements a cache system using structural VHDL as part of a computer engineering course. The design models cache behavior at the hardware level, including memory access, control logic, and data storage.

An extended version of the project includes a 2-way set associative cache with replacement logic, demonstrating more advanced cache design concepts.

## Purpose
The goal of this project is to understand how cache memory operates at a low level by designing and simulating a working cache system. This includes exploring concepts such as:
- Cache organization
- Memory access timing
- Set associativity
- Replacement policies

## Technologies Used
- VHDL (structural design)
- Cadence Xcelium (simulation)
- Digital design concepts (FSMs, latches, control logic)

## Features
- Structural VHDL implementation of a cache system
- Support for memory read/write operations
- 2-way set associative cache (extra credit)
- Cache control logic using FSM design
- Simulation testbenches for verification

## Project Structure

- `*.vhd` → VHDL source files for cache components  
- `testbench/` → Simulation testbench files  
- `README.md` → Project documentation

## My Contribution

I designed and implemented the cache system using structural VHDL. My work included:

- Designing the cache datapath and control logic
- Implementing address breakdown and mapping logic
- Developing an FSM-based cache controller
- Extending the design to a 2-way set associative cache with replacement logic
- Debugging and validating functionality using Cadence Xcelium simulations

## Challenges & Learning

A key challenge was ensuring correct cache behavior while maintaining synchronization between the control and datapath components. Debugging timing-related issues and verifying memory access correctness required iterative testing and simulation.

Through this project, I strengthened my understanding of:

- Hardware-level system design using VHDL
- Cache architecture and memory hierarchy
- Debugging and validating digital systems through simulation tools
