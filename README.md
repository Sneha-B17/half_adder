# Half Adder in Verilog

This is a basic Verilog project that implements a Half Adder and tests it using a Verilog testbench.

## 📁 Files

- half_adder.v – Verilog module for half adder
- half_adder_tb.v – Testbench for verifying the design

## 📚 Description

A half adder is a combinational logic circuit that adds two single-bit binary numbers. It produces a sum and a carry output.

### 🧠 Truth Table

| A | B | Sum | Carry |
|---|---|-----|--------|
| 0 | 0 |  0  |   0    |
| 0 | 1 |  1  |   0    |
| 1 | 0 |  1  |   0    |
| 1 | 1 |  0  |   1    |

## ▶ How to Simulate (Using Icarus Verilog)

1. Open terminal and run:
   ```bash
   iverilog -o half_adder_sim half_adder.v half_adder_tb.v
   vvp half_adder_sim
