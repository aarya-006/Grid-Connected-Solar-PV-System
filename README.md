# Grid-Connected Solar PV System with MPPT and Power Quality Analysis

## Overview
This project presents the design and simulation of a grid-connected solar photovoltaic (PV) system using MATLAB/Simulink. The system integrates a PV array, P&O MPPT algorithm, DC-DC boost converter, grid-tied inverter, SRF-PLL synchronization, and dual-loop current control.

## Objectives
- Extract maximum power from the PV array under varying irradiance conditions.
- Synchronize inverter output with the utility grid.
- Maintain stable DC-link voltage.
- Achieve unity power factor operation.
- Analyze power quality and verify IEEE 1547 compliance.

## System Architecture
PV Array
→ MPPT (P&O)
→ DC-DC Boost Converter
→ DC Link
→ 3-Phase Inverter
→ LCL Filter
→ Utility Grid

## Features
- PV array modeling
- P&O MPPT implementation
- DC-DC boost converter
- SRF-PLL grid synchronization
- dq current control
- LCL filter design
- THD analysis
- IEEE 1547 compliance verification

## Tools Used
- MATLAB
- Simulink
- Simscape Electrical

## Expected Results
- MPPT efficiency > 98%
- Grid current THD < 5%
- Power factor > 0.99
- Stable DC-link voltage regulation

## Status
🚧 Currently under development
