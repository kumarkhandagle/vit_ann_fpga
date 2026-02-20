**Comparative Study of ANN and SNN on FPGA Platform**

This repository contains a lightweight FPGA codebase designed to demonstrate Artificial Neural Network (ANN) inference on hardware.
Provide a working hardware foundation where we can deploy and test small quantized neural networks on an FPGA. 


**Project Overview**
1.The design includes:
2.A small INT8 systolic array for matrix multiplication
3.Basic control logic for loading weights and activations
4.Quantization support (INT8 arithmetic)
5.Simulation testbench for verification
6.FPGA synthesis-ready RTL

The architecture is suitable for implementing fully connected (dense) neural network layers and experimenting with small ANNs.

**Project Structure**
```
FPGA_ANN/
│
├── rtl/
│
├── docs/
│   ├── diagrams/
│   ├── specs/
│   ├── Tutorial/
│   └── other_resources/
│
└── tb/
|   └── testbench/
|
└── python_codes/
    └── testbench/


```
