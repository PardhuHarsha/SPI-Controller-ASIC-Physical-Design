# SPI ASIC Physical Design using Qflow

This project implements the physical design flow of a Serial Peripheral
Interface (SPI) using the Qflow open-source ASIC design environment
with the OSU018 technology library.

## Flow

RTL → Synthesis → Placement → Routing → STA → DRC → LVS → GDSII

## Final Results

- Technology: OSU018
- Routing: 22209 routes completed
- Failed routes: 0
- STA paths analyzed: 321
- Worst setup delay: 4.161 ns
- Maximum operating frequency: 240.33 MHz
- Minimum hold delay: 267 ps
- Hold violations: 0
- DRC errors: 0
- LVS errors: 0
- LVS devices matched: 3103
- LVS nets matched: 3150
- GDSII generation: Successful

## Tools

- Ubuntu Linux
- Qflow
- Yosys
- GrayWolf
- Qrouter
- Magic
- Netgen
