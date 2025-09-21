# RTL Design And Synthesis Using Sky130


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

### 1. **Understanding RTL Design Principles**
- **Verilog RTL Modeling:** Learned that RTL (Register Transfer Level) is a hardware description methodology that describes the flow of digital signals between registers and the logical operations performed on those signals.
- **Design Hierarchy:** Emphasized the importance of modular design—building complex systems from smaller, manageable modules.
- **Coding Styles:** Discovered different coding styles for flip-flops, such as using `always @(posedge clk)` blocks, which are essential for synchronous designs.

---

## My Notes and Insights

- **Design Workflow:** The typical flow I’m learning involves writing RTL → simulating with testbenches → synthesizing with Yosys → analyzing waveforms and debugging.
- **Importance of Clear Coding Practices:** Proper naming conventions and modular code make debugging and future modifications much easier.
- **Open-Source Ecosystem:** Sky130 and Yosys are powerful tools that democratize hardware design, making it accessible for students and hobbyists.

---

## Next Steps

- Deepen my understanding of timing libraries and their impact on synthesis.
- Experiment with different flip-flop coding styles to optimize for area and speed.
- Continue practicing testbench creation to improve verification skills.

---

This initial week has laid a strong foundation for my RTL design journey. I look forward to applying these concepts in more complex designs and exploring optimization techniques in the upcoming weeks!

## Acknowledgement 👑
I am thankful to [**Kunal Ghosh**](https://github.com/kunalg123) and Team **[VLSI System Design (VSD)](https://vsdiat.vlsisystemdesign.com/)** for the opportunity to participate in the ongoing **RISC-V SoC Tapeout Program**.  

I also acknowledge the support of **RISC-V International**, **India Semiconductor Mission (ISM)**, **VLSI Society of India (VSI)**, and [**Efabless**](https://github.com/efabless) for making this initiative possible.  
<div align="center">
