# RISC-V-Instruction-Set-Analysis

# Python-based RISC-V Simulation Model

This project demonstrates the simulation and analysis of basic RISC-V instructions using two tools:
- **Venus (Web-based RISC-V Simulator)** – for executing and testing assembly instructions.
- **Python-based Model** – for tracking execution cycles, calculating CPI (Cycles Per Instruction), and measuring performance.

## Files
- **Python-based RISC-V simulation model.ipynb** — Python notebook that simulates instruction execution and calculates performance metrics.
- **riscv_add_equal.s** — RISC-V assembly source code tested in the Venus simulator.
- **README.md** — Project description.

## Results
- Arithmetic instructions (ADD, SUB) completed in 1 cycle each.
- Memory instructions (LW, SW) required 3–5 cycles due to memory latency.
- Calculated CPI: **2.33**
- Execution time (1 GHz clock): **14 nanoseconds**

## Tools Used
- [Venus RISC-V Simulator](https://venus.cs61c.org/)
- Python 3.x with Jupyter Notebook

---

### Author
**Nur Aishah Binti Mohd Yussof**  
BACHELOR OF SCIENCE(Hons.) IN INFORMATION TECHNOLOGY   
MALAYSIA UNIVERSITY of SCIENCE and TECHNOLOGY
