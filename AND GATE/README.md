# AND Gate Using Verilog

## Overview
This project implements a 2-input AND gate using Verilog HDL. It includes the Verilog source code, testbench, and simulation results.

## Truth Table

| A | B | Y |
|---|---|---|
| 0 | 0 | 0 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 1 |

## Files

| File | Description |
|------|-------------|
| and_gate.v | Verilog code for AND gate |
| and_gate_tb.v | Testbench for verification |
| waveform.png | Simulation waveform |
| and_gate.vcd | Waveform file |

## Verilog Code

```verilog
assign Y = A & B;
```

## Simulation

The testbench applies all possible input combinations and verifies the output.

## Expected Output

```
A=0 B=0 Y=0
A=0 B=1 Y=0
A=1 B=0 Y=0
A=1 B=1 Y=1
```

## Software Used

- Verilog HDL
- Icarus Verilog
- GTKWave
- VS Code

## Author

Your Name