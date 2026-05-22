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

<p align="center">
  <img src="https://github.com/MHChowdhury179/scr-class-b-class-c-commutation-circuits/blob/961f926ce1eaef63b7e00e30d26ddea5a62aa431/Circuit%20diagram%20of%20Class%20B%20commutation..jpg" width="500"><br>
  <em>Figure: Circuit Diagram</em>
</p>

<p align="center">
  <img src="https://github.com/MHChowdhury179/scr-class-b-class-c-commutation-circuits/blob/737b7c31c64cd6ad146efe63647a22a585f7e8c4/Experimental%20set-up%20picture%20of%20Class%20B%20commutation.jpg" width="500"/>
  <br>
  <em>Figure: Experimental Setup</em>
</p>

**Measured and analyzed outputs:**
<p align="center">
  <img src="https://github.com/MHChowdhury179/scr-class-b-class-c-commutation-circuits/blob/6156372b9d945d7c443a47a887959b426f53a30e/B_gate%20pulse.png" width="500"><br>
  <em>Figure: SCR Gate Pulse</em>
</p>

<p align="center">
  <img src="https://github.com/MHChowdhury179/scr-class-b-class-c-commutation-circuits/blob/360dbe3f8ba314d76462c4d4af73a83f6964e2c9/B_IL.png" width="500"><br>
  <em>Figure: Inductor/load current waveform </em>
</p>

<p align="center">
  <img src="https://github.com/MHChowdhury179/scr-class-b-class-c-commutation-circuits/blob/1e08b6a69843f9694394f427f88ea4e756655edb/B_VSCR.png" width="500"><br>
  <em>Figure: Voltage across SCR </em>
</p>

<p align="center">
  <img src="https://github.com/MHChowdhury179/scr-class-b-class-c-commutation-circuits/blob/80b94c683be393085f26b25959f57a44028ba5d8/Simulink%20model%20of%20Class%20B%20commutation%20circuit..jpg" width="500"><br>
  <em>Figure: Simulink Model</em>
</p>

<p align="center">
  <img src="https://github.com/MHChowdhury179/scr-class-b-class-c-commutation-circuits/blob/2d9c5af121220014fa4c53f21888763ee025f437/Gate%20pulse%20(Ig)%20and%20Load%20current%20(IL)%20obtained%20from%20Simulink%20of%20Class%20B%20commutation..jpg" width="500"><br>
  <em>Figure: Gate pulse and Load current obtained from Simulink</em>
</p>

<p align="center">
  <img src="https://github.com/MHChowdhury179/scr-class-b-class-c-commutation-circuits/blob/a4127dd640c2a987c85f2f0e8b444f42344cd5cb/Gate%20pulse%20(Ig)%2C%20Current%20through%20SCR%20(ISCR)%20and%20Voltage%20across%20SCR%20(VSCR)%20obtained.jpg" width="500"><br>
  <em>Figure: Gate pulse, Current through SCR and Voltage across SCR (VSCR) obtained from Simulink</em>
</p>

### Experiment 2: Class C Commutation Circuit
The Class C commutation circuit was experimentally implemented using two SCRs, resistors, and a commutating capacitor. Gate pulses were applied to SCR1 and SCR2 to observe the commutation process. The circuit was also modeled in MATLAB/Simulink, and the simulation outputs were compared with the practical oscilloscope waveforms.

<p align="center">
  <img src="https://github.com/MHChowdhury179/scr-class-b-class-c-commutation-circuits/raw/53ce29cc6838b0945c979173598ca53da858fed3/Circuit%20diagram%20of%20Class%20C%20commutation..jpg" width="500"><br>
  <em>Figure: Circuit Diagram</em>
</p>

<p align="center">
  <img src="https://github.com/MHChowdhury179/scr-class-b-class-c-commutation-circuits/raw/7c2b0ea44cc310fcc50794a9105f11cb3c536ac9/Experimental%20set-up%20picture%20of%20Class%20C%20commutation..jpg" width="500"><br>
  <em>Figure: Experimental Setup</em>
</p>

**Measured and analyzed outputs:**

<p align="center">
  <img src="https://github.com/MHChowdhury179/scr-class-b-class-c-commutation-circuits/raw/3960f1a52bf01bcd53fef068a9e13f98f1c8baa6/C-gate%20pulses.png" width="500"><br>
  <em>Figure: Gate pulses of SCR1 and SCR2</em>
</p>

<p align="center">
  <img src="https://github.com/MHChowdhury179/scr-class-b-class-c-commutation-circuits/raw/e1532db445b7c1f8efec39b52ab79b3fdec01cb9/C_IR1.png" width="500"><br>
  <em>Figure: Current through Resistor1</em>
</p>

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
