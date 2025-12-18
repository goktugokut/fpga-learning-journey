# FPGA VHDL Learning Journey

## Overview

This repository documents my personal learning journey in FPGA design using VHDL. It contains self-designed projects that gradually build up from fundamental digital logic concepts to more advanced FPGA-oriented system designs.

The focus of this repository is **learning by building**, with an emphasis on clean architecture, readability, and proper documentation.

---

## Motivation

As an Electrical Engineering student at the Technical University of Munich (TUM), I aim to develop strong practical skills in digital hardware design. Beyond university coursework, I use this repository to:

* Reinforce theoretical concepts through hands-on implementation
* Practice writing clean, synthesizable VHDL
* Build a solid project portfolio for FPGA-related internships
* Learn professional documentation and version control habits

All projects in this repository are independently implemented and are **not direct copies of any university assignments**.

---

## Repository Structure

```text
fpga-vhdl-learning-journey/
├── basics/            # Gates, multiplexers, simple combinational logic
├── sequential/        # Flip-flops, counters, registers
├── fsm/               # Finite State Machine examples
├── packet_processing/ # Custom data packetizer experiments
├── simulation/        # Testbenches and simulation notes
└── README.md
```

---

## Design Principles

* Vendor-independent VHDL coding style
* Synthesizable and simulation-friendly designs
* Modular and reusable architectures
* Clear signal naming and comments
* Step-by-step complexity increase

---

## Tools & Technologies

* **Hardware Description Language:** VHDL
* **Target Platforms:** FPGA (vendor-independent)
* **Simulation:** ModelSim / Vivado Simulator
* **Version Control:** Git & GitHub

---

## How to Use This Repository

Each folder represents a standalone learning topic. Projects typically include:

* VHDL source files
* A short description of the design goal
* A testbench for simulation
* Notes on design decisions

The projects are intended for educational and demonstrational purposes.

---

## Academic Integrity Notice

This repository contains **original implementations created outside graded university submissions**. While the designs may be inspired by general digital design concepts taught in academic courses, all architectural decisions and code are my own.

---

## Future Work

* UART transmitter/receiver
* Parametric packetizer with error detection
* FIFO-based data buffering
* VGA or simple video controller
* Small FPGA-based system project

---

## About Me

Electrical Engineering student at TUM with a strong interest in FPGA design, digital systems, and hardware-oriented problem solving.

This repository represents my continuous learning progress rather than finished commercial products.
