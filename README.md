# CNN Hardware Accelerator on FPGA

> **Status:** RTL reconstruction in progress.

This project explores the implementation of a convolutional neural-network accelerator in Verilog using the Xilinx Vivado development flow. It represents practical work in RTL design, FPGA-oriented architecture, and verification-aware hardware development.

## Engineering focus

- Verilog RTL design
- FPGA development using Vivado
- CNN accelerator architecture
- Simulation and testbench-driven verification
- Synthesis and implementation workflow

## Repository plan

```text
├── rtl/             # Recreated Verilog design modules
├── tb/              # Testbenches and simulation assets
├── constraints/     # Board constraints, when applicable
├── docs/            # Architecture and verification notes
└── results/         # Reproduced, verified implementation reports
```

## Reconstruction roadmap

- [ ] Document the original accelerator dataflow and supported operations
- [ ] Recreate RTL modules from verified design notes
- [ ] Add self-checking testbenches
- [ ] Re-run Vivado synthesis and implementation
- [ ] Publish only reproducible utilisation, timing, and simulation results

## Why this matters

Rather than presenting a black-box AI project, this repository focuses on the hardware path: how neural-network computation can be represented, tested, and implemented as digital logic.

## Author

**D. Giridhar**  
[LinkedIn](https://www.linkedin.com/in/duddekunta-giridhar-799b88302/) · [GitHub](https://github.com/DGiridhar2085)

## License

MIT License planned for recreated source code.
