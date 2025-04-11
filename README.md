# alexnet-hw-accelerator-verilog

## Description

This project implements a simplified hardware accelerator for the initial layers of **AlexNet**, a landmark convolutional neural network architecture. The design is written in **Verilog RTL** and includes three core components:

- 2D Convolution
- ReLU Activation
- Max Pooling

It was developed as part of a hardware/digital design course project focused on building ASIC-style deep learning accelerators.

## Key Features

- RTL implementation of 2D convolution
- Pipelined ReLU module
- 2x2 max pooling layer
- FSM-based control flow
- Modular design for clarity and testing
- Simulated memory modules for weights and input feature maps

## Project Files

```bash
.
├── processor.v        # Top-level module connecting convolution, ReLU, and pooling
├── fsm.v              # FSM for operation sequencing
├── main.v             # Central control logic
├── max_pool.v         # Max pooling implementation
├── ReLU.v             # ReLU activation unit
├── mem8_105.v         # Example feature map memory module
├── mem8_140.v         # Additional memory module
├── mem23_9.v          # Additional memory module
├── mem88_11.v         # Additional memory module
├── processor_tb.vt    # Testbench for top-level module
```
