# SCR Class B & C Commutation: Experimental & Simulink Analysis

## Overview
This project presents the experimental implementation, simulation modeling, and output waveform analysis of SCR-based Class B and Class C commutation circuits.

## Project Objectives
- Implemented SCR-based Class B and Class C commutation circuits in a laboratory setup.
- Developed MATLAB/Simulink models for both commutation circuits.
- Captured gate pulse, SCR current, load current, and SCR voltage waveforms using an oscilloscope.
- Analyzed SCR turn-off behavior and forced commutation characteristics.
- Compared experimental waveforms with Simulink simulation outputs.

## Experiments Covered

### Experiment 1: Class B Commutation Circuit
The Class B commutation circuit was practically implemented using an SCR, inductor, capacitor, and resistive load. The circuit output was observed through a laboratory experimental setup, where key waveforms were captured using an oscilloscope. A MATLAB/Simulink model of the same circuit was also developed to verify and compare the experimental results. 
1. Circuit Diagram:
![image alt](https://github.com/MHChowdhury179/scr-class-b-class-c-commutation-circuits/blob/961f926ce1eaef63b7e00e30d26ddea5a62aa431/Circuit%20diagram%20of%20Class%20B%20commutation..jpg) 


**Measured and analyzed outputs:**
- SCR gate pulse
- Inductor/load current waveform
- Voltage across SCR
- SCR turn-off behavior
- Comparison between oscilloscope and Simulink waveforms

### Experiment 2: Class C Commutation Circuit
The Class C commutation circuit was experimentally implemented using two SCRs, resistors, and a commutating capacitor. Gate pulses were applied to SCR1 and SCR2 to observe the commutation process. The circuit was also modeled in MATLAB/Simulink, and the simulation outputs were compared with the practical oscilloscope waveforms.

**Measured and analyzed outputs:**
- Gate pulses of SCR1 and SCR2
- Current through resistor
- Current through SCR1
- Voltage across SCR1
- Turn-off time behavior
- RC time constant effect on commutation
- Comparison between practical and simulated waveforms

## Tools and Technologies
- MATLAB/Simulink for circuit modeling and simulation
- Oscilloscope for practical waveform measurement
- SCR/Thyristor trainer board for hardware implementation
- Power electronics laboratory setup
- DC power supply
- Passive components: resistor, capacitor, and inductor
- Experimental waveform analysis and simulation result comparison

## Repository Structure
```text
├── report/
│   └── class-b-class-c-commutation-report.pdf
├── simulink-models/
│   ├── class-b-commutation.slx
│   └── class-c-commutation.slx
├── figures/
│   ├── class-b-circuit-diagram.png
│   ├── class-b-experimental-setup.png
│   ├── class-b-waveforms.png
│   ├── class-c-circuit-diagram.png
│   ├── class-c-experimental-setup.png
│   └── class-c-waveforms.png
└── README.md
