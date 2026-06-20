# 8x4-6T-SRAM-Array-Form-Schematic-to-Layout-Cadence

Overview
This project presents the design, characterization, and layout implementation of an 8×4 SRAM array using custom 6T SRAM cells in GPDK 90nm CMOS technology. The complete memory subsystem was designed in Cadence Virtuoso and includes essential peripheral circuits required for reliable read and write operations.

The work covers schematic design, transient verification, SRAM characterization, full-custom layout implementation, and physical verification through DRC and LVS checks.

Key Features
Custom 6T SRAM Bitcell Design
8×4 SRAM Array Architecture
Row Decoder Implementation
Precharge Circuit Design
Differential Sense Amplifier Design
Functional Read, Write, and Hold Verification
Full-Custom Layout Development
Clean DRC Verification
Clean LVS Verification
Technology and Tools
Category	Details
Technology	GPDK 90nm CMOS
Design Environment	Cadence Virtuoso
Simulation	Cadence Spectre
Physical Verification	Assura DRC/LVS
SRAM Architecture

The memory subsystem consists of:
8×4 SRAM Array
Row Decoder
Precharge Circuit
Differential Sense Amplifier
Custom 6T SRAM Bitcells

These blocks were integrated to perform complete memory read and write operations.
Performance Results
Parameter	Value
Read Delay	5.21 ps
Write '0' Delay	16.09 ps
Write '1' Delay	26.23 ps
Hold SNM	180 mV
Cell Area	7.88 µm²
DRC Violations	0
LVS Mismatches	0

Verification
Functional Verification
Read Operation Verification
Write Operation Verification
Hold State Verification
Peripheral Circuit Validation
Physical Verification
DRC Clean
LVS Matched
No Device Mismatches
No Net Mismatches

Repository Contents
8x4-6T-SRAM-Array-Form-Schematic-to-Layout-Cadence
│ 
├── Report/ 
  │ 
  └── SRAM_Array_Report.pdf 
│ 
├── Images/ 
  │ 
  ├── SRAM_Cell_Schematic.png 
  │ 
  ├── SRAM_Cell_Layout.png 
  │ 
  ├── Decoder.png 
  │ 
  ├── Sense_Amplifier.png 
  │ 
  ├── Precharge_Circuit.png 
  │ 
  ├── SRAM_Array.png 
  │ 
  ├── Waveforms.png 
│ 
└── README.md

Key Learning Outcomes
SRAM Memory Architecture Design
Peripheral Circuit Integration
Static Noise Margin Analysis
Memory Characterization
Full-Custom Layout Design
DRC and LVS Verification Flow
Cadence Virtuoso Design Methodology

Author
Nikhil Jindal
Electronics and Communication Engineering
LinkedIn: www.linkedin.com/in/nikhil-jindal-074a34218
