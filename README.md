# Assaf Afriat – Digital Design & Verification Portfolio

Welcome!  
This repository contains my professional CVs and selected projects, focused on:

- ASIC / FPGA Verification (UVM, SystemVerilog)
- Digital Design (RTL, FSMs, CDC, timing-aware design)

---

## 📄 Curriculum Vitae

### 🔹 Combined – Digital Design & Verification
- HTML: [cv/cv_combined.html](cv/cv_combined.html)
- PDF:  [cv/cv_combined.pdf](cv/cv_combined.pdf)

### 🔹 Verification Engineer
- HTML: [cv/cv_verification.html](cv/cv_verification.html)
- PDF:  [cv/cv_verification.pdf](cv/cv_verification.pdf)

### 🔹 Digital Design Engineer
- HTML: [cv/cv_design.html](cv/cv_design.html)
- PDF:  [cv/cv_design.pdf](cv/cv_design.pdf)

---

## 🧠 Skills Snapshot
- SystemVerilog (RTL & UVM)
- Functional Coverage & Assertions
- Testbench Architecture
- FSM design, CDC, reset strategies
- Simulation & Debug (ModelSim, Icarus, GTKWave)

---

## 🚀 Featured Projects

### 🧪 UVM Verification Project – Configurable Packet Modifier (CPM)
- Full UVM-based verification environment (agents, RAL, coverage, scoreboard)
- Live HTML demo available
- Production-style project structure

🔗 **Project Repository:**  
[github.com/Assaf-Afriat/uvm-cpm-packet-modifier](https://github.com/Assaf-Afriat/uvm-cpm-packet-modifier)

🔗 **Live Demo:**  
[assaf-afriat.github.io/uvm-cpm-packet-modifier](https://assaf-afriat.github.io/uvm-cpm-packet-modifier/deliverables/project_demo.html)

---

### 🔧 RTL Design Project – UART Image Processing SoC
- Multi-clock SystemVerilog SoC for real-time 256x256 RGB image transfer at 5.5 Mbaud
- Full protocol stack: PHY (32x oversampling), MAC (frame-safe), Classifier, CDC synchronizers
- DMA-style burst engine with dedicated RX/TX sequencers and color-separated SRAM
- 27 RTL modules across two clock domains (176 MHz / 100 MHz), 6 register files
- Synthesized and hardware-verified on Digilent Nexys A7-100T (Artix-7)

🔗 **Project Repository:**  
[github.com/Assaf-Afriat/uart-image-processing-soc](https://github.com/Assaf-Afriat/uart-image-processing-soc)

🔗 **Live Demo:**  
[assaf-afriat.github.io/uart-image-processing-soc](https://assaf-afriat.github.io/uart-image-processing-soc/docs/project_demo.html)

---

### 🧪 UVM Verification Project – ALU with Variable Latency & FIFO
- Complete UVM verification environment for an 8-bit ALU with output FIFO and backpressure
- 8 ALU operations (ADD, SUB, MUL, AND, XOR, SLL, SRL, DIV) with variable latency (2-8 cycles)
- 11 SVA assertions (protocol, reset, latency, FIFO integrity)
- 8 covergroups with cross coverage, 10 callbacks (driver, monitor, scoreboard)
- 6 test types: sanity, stress, coverage-driven, regression, callback demo, full regression
- Valid/Ready handshaking with random backpressure testing

🔗 **Project Repository:**  
[github.com/Assaf-Afriat/uvm-alu-project](https://github.com/Assaf-Afriat/uvm-alu-project)

🔗 **Live Demo:**  
[assaf-afriat.github.io/uvm-alu-project](https://assaf-afriat.github.io/uvm-alu-project/docs/project_demo.html)

---

