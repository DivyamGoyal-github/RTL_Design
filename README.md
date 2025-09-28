# RTL Design And Synthesis Using Sky130


This repository is a structured record of my **intensive 5-day learning journey** in RTL Design and Synthesis using open-source tools like **Icarus Verilog, GTKWave, Yosys**, and **Sky130 PDKs**.  

The bootcamp focused on bridging **RTL coding, simulation, synthesis, optimization, and gate-level verification**, covering both theoretical concepts and practical labs.

Welcome to my notes from Week 1 of the RTL Design and Synthesis by VLSI System Design (VSD). This week focused on building a solid foundation in Verilog RTL design, simulation, and the basics of digital circuit synthesis using Sky130 PDK. I’ve compiled my key learnings and insights below to reinforce the concepts and guide my ongoing practice.

---
## Prerequisites

- Basic understanding of digital logic (gates, flip-flops, multiplexers, etc.)
- Familiarity with Linux shell commands
- A Linux environment (or WSL on Windows/macOS)
- Tools: `git`, `iverilog`, `gtkwave`, `yosys`, and a text editor

---
## Structure
The repository is organized by day, each with a dedicated folder and README:

- [Day 1: Introduction to Verilog RTL Design & Synthesis](Day_1/README.md)
- [Day 2: Timing Libraries, Synthesis Approaches, and Efficient Flip-Flop Coding](Day_2/README.md)
- [Day 3: Combinational and Sequential Optimization](Day_3/README.md)
- [Day 4: Gate-Level Simulation (GLS), Blocking vs. Non-Blocking in Verilog, and Synthesis-Simulation Mismatch ](Day_4/README.md)
- [Day 5: Optimization in Synthesis ](Day_5/README.md)

Each day’s README includes:
- Clear explanations of the day’s concepts
- Step-by-step practical labs with code and screenshots
---

## Key Takeaways from Week 1
### **Day 1 – RTL Foundations, Simulation & Synthesis Tools**
- **Concepts Covered:**
  - Introduction to RTL design with Verilog.
  - Setup and usage of **Icarus Verilog** for simulation.
  - Waveform analysis with **GTKWave**.
  - Introduction to **Yosys** and logic synthesis flow.
  - Familiarization with **Sky130 PDKs** for real silicon mapping.
- **Labs Completed:**
  - Simulated basic combinational circuits (AND, OR, MUX) using Icarus Verilog.
  - Waveform analysis in GTKWave.
  - Synthesized a simple adder circuit using Yosys.
  - Observed technology-mapped gates with Sky130 libraries.
- **Outcome:**  
  Gained hands-on comfort with Verilog simulation and basic synthesis flows.

---

### **Day 2 – Timing Libraries & Robust RTL Coding**
- **Concepts Covered:**
  - What are timing libraries (`*.lib`) and why they matter.
  - Hierarchical vs Flat synthesis – optimization trade-offs.
  - Efficient flop coding styles to ensure timing-friendly RTL.
- **Labs Completed:**
  - Compared hierarchical vs flat synthesis results.
  - Coded different DFF styles and analyzed their impact on synthesis.
- **Outcome:**  
  Learned how coding style directly affects timing, area, and synthesis efficiency.

---

### **Day 3 – Combinational & Sequential Optimizations**
- **Concepts Covered:**
  - Synthesis optimizations: how tools simplify logic.
  - **Combinational optimizations:** constant folding, redundant gate removal.
  - **Sequential optimizations:** FSM simplification, unused register elimination.
  - Proper handling of unused outputs.
- **Labs Completed:**
  - Verified Boolean simplification automatically performed during synthesis.
  - Observed state machine reduction in synthesized designs.
  - Experimented with unused output signals and their effect on synthesis.
- **Outcome:**  
  Developed understanding of how synthesis tools "clean up" designs for efficiency.

---

### **Day 4 – Gate-Level Simulation & RTL/Synthesis Mismatches**
- **Concepts Covered:**
  - Running **Gate-Level Simulation (GLS)** with netlists.
  - Identifying **simulation vs synthesis mismatches**.
  - Blocking (`=`) vs Non-blocking (`<=`) assignments in procedural code.
- **Labs Completed:**
  - Compared RTL simulation vs GLS waveforms.
  - Created intentional mismatches using blocking assignments.
  - Debugged sequence failures in GLS.
- **Outcome:**  
  Ability to write synthesis-safe RTL and debug synthesis-simulation mismatches.

---

### **Day 5 – Control Structures, Loops & Advanced Coding**
- **Concepts Covered:**
  - Correct handling of **if-case constructs** to avoid latch inference.
  - Understanding **overlapping vs parallel case statements**.
  - Using **for loops** and **for-generate** for scalable RTL.
- **Labs Completed:**
  - Wrote incomplete if/case RTL and observed unintended latch generation.
  - Explored overlapping case behavior.
  - Designed scalable structures (barrel shifter/register replications) using loops and generate.
- **Outcome:**  
  Mastery of advanced RTL coding constructs ensuring correctness and scalability.

---

## ⚡ Tools & Technologies Used
- **Verilog HDL**
- **Icarus Verilog** (simulation)
- **GTKWave** (waveform visualization)
- **Yosys** (logic synthesis)
- **Sky130 PDKs** (real silicon standard cell libraries)

---

## 🏆 Week 1 Achivements
- Write Verilog RTL that is **simulation-correct and synthesis-friendly**.  
- Perform simulation with Icarus Verilog and debug waveforms in GTKWave.  
- Run synthesis flows in Yosys and map to Sky130 gates.  
- Understand timing libraries and design trade-offs.  
- Optimize designs at both combinational and sequential levels.  
- Confidently perform **Gate-Level Simulation (GLS)** to verify post-synthesis behavior.  
- Avoid RTL pitfalls like incomplete case statements, blocking assignments, and unintended latches.  

---

## My Notes and Insights

- **Design Workflow:** The typical flow I’m learning involves writing RTL → simulating with testbenches → synthesizing with Yosys → analyzing waveforms and debugging.
- **Importance of Clear Coding Practices:** Proper naming conventions and modular code make debugging and future modifications much easier.
- **Open-Source Ecosystem:** Sky130 and Yosys are powerful tools that democratize hardware design, making it accessible for students and hobbyists.

---

## 🌟 Reflection
This 5-day week on RTL Design has given me **end-to-end confidence** in the digital design flow: from coding RTL, simulating it, synthesizing with real libraries, to debugging mismatches at gate-level simulation. I now approach RTL **not just as code, but as real hardware blueprints**.


This initial week has laid a strong foundation for my RTL design journey. I look forward to applying these concepts in more complex designs and exploring optimization techniques in the upcoming weeks!

## Acknowledgement 👑
I am thankful to [**Kunal Ghosh**](https://github.com/kunalg123) and Team **[VLSI System Design (VSD)](https://vsdiat.vlsisystemdesign.com/)** for the opportunity to participate in the ongoing **RISC-V SoC Tapeout Program**.  

I also acknowledge the support of **RISC-V International**, **India Semiconductor Mission (ISM)**, **VLSI Society of India (VSI)**, and [**Efabless**](https://github.com/efabless) for making this initiative possible.  
<div align="center">
