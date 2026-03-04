<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This project implements the VSL (Very Simple Logic) Logo using Verilog for the Tiny Tapeout initiative. It demonstrates a compact digital design that renders or processes logo-related logic patterns in hardware, showcasing basic digital logic design principles suitable for silicon implementation through the Tiny Tapeout program.

## How to test

1. Ensure you have Verilog simulation tools installed (e.g., Icarus Verilog, Verilator)
2. Review the testbench files included in the repository
3. Run simulations using the provided Makefile:
   ```bash
   make test
   ```
4. Verify the output matches expected logo generation/rendering patterns
5. For hardware implementation, use the provided Makefile to synthesize:
   ```bash
   make build
   ```

## External hardware

No external hardware required. This is a pure Verilog design intended for FPGA or ASIC implementation through Tiny Tapeout.
