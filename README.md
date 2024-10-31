# Electronic_Project1 : Electronic Amplifier Design and Analysis Project

## Overview
This project involves the design and analysis of an electronic amplifier circuit, simulating various transistor configurations using SPICE software, and evaluating critical parameters including voltage gains, saturation voltages, and harmonic distortion (THD).

## Project Structure

- **SPICE Simulations**: NPN and PNP transistors were analyzed across multiple biasing conditions to determine \( V_{BE(on)} \) and \( V_{CE(sat)} \) at different collector currents.
- **Amplifier Design**: A fully differential amplifier was designed with specified gain, common-mode rejection ratio (CMRR), and power requirements.
- **THD Analysis**: The Total Harmonic Distortion was computed for the amplifier circuit to ensure signal fidelity under specific output swing conditions.

## Files

- `elec_project.pdf`: Detailed report on the project objectives, methodologies, simulation results, and discussions.
- `Draft1.asc`: SPICE circuit design file for running the simulations described in the report.
- `Project1 (3).pdf`: Documentation outlining the technical requirements, component specifications, and circuit schematics.

## Requirements

- **Software**: SPICE or equivalent circuit simulation software.

## Results Summary

The project achieved the targeted amplifier performance, with simulation data supporting calculated values for gains, \( V_{BE(on)} \), \( V_{CE(sat)} \), and CMRR. THD was maintained within acceptable limits for signal integrity.

## Usage

1. Open the `.asc` file in SPICE to view and simulate the circuit.
2. Refer to `elec_project.pdf` and `Project1 (3).pdf` for step-by-step guidance and analysis.

