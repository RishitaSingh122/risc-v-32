# risc-v-32
 A complete RISC-V based microcontroller featuring a 5-stage pipelined CPU, interrupt handling, MMU, and floating-point support. Designed from scratch for system-level insight into embedded and VLSI design.
# risc-v-32

A complete RISC-V based microcontroller built from scratch, featuring:

- 🧠 5-stage pipelined CPU
- ⚡ Interrupt handling
- 🧮 Floating Point Unit (FPU)
- 🧭 Memory Management Unit (MMU)
- 🔌 Custom bus interface
- 🧪 Testbenches and simulation support

Designed as a system-level exploration into both **embedded** and **VLSI** design.

---

## 🚀 Project Goals

- Implement a 32-bit RV32IMAF-compatible CPU core
- Integrate a programmable interrupt controller and trap logic
- Add MMU for memory protection and address translation
- Design and simulate a basic FPU
- Create a minimal SoC with memory map and bus
- Run custom programs written in RISC-V assembly

---

## 📁 Folder Structure


risc-v-32/
├── core/         # Pipelined CPU design
├── mmu/          # Memory Management Unit
├── intc/         # Interrupt controller
├── fpu/          # Floating point unit
├── bus/          # Bus interface
├── test/         # Testbenches
├── programs/     # Sample assembly programs
└── docs/         # Block diagrams, notes, specs
