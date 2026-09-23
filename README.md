# Dynamic Bandwidth Scheduling

Simulation model studying uplink bandwidth allocation in WCDMA (Wideband Code Division Multiple Access) networks. This project implements dynamic scheduling algorithms — with optional deep learning components — and compares their performance against traditional static allocation methods.

## Overview

Uplink bandwidth in WCDMA networks is a shared, limited resource, and how it's allocated across users directly affects network efficiency and quality of service. Static allocation methods assign bandwidth using fixed rules, which don't adapt well to changing traffic conditions. This project explores a dynamic scheduling approach that adjusts allocation in real time based on network conditions, and evaluates whether adding a deep learning component further improves scheduling efficiency.

## Tech Stack

- **MATLAB / Simulink** — simulation environment and model implementation
- **Deep Learning (MATLAB Deep Learning Toolbox)** — optional learning-based scheduling component

## Key Features

- Simulation model of uplink bandwidth allocation in a WCDMA network
- Dynamic scheduling algorithm for real-time bandwidth allocation
- Optional deep learning-based scheduler for comparison against rule-based dynamic scheduling
- Benchmarking against static (fixed) allocation methods
- Demonstrated efficiency improvements over static allocation

## Results

The dynamic scheduling approach showed improved bandwidth efficiency compared to static allocation methods, with the deep learning-enhanced variant explored as a further optimization.

## Requirements

- MATLAB (R2021a or later recommended)
- Simulink
- Deep Learning Toolbox (only required if running the deep learning-based scheduler)

## Usage

1. Clone this repository.
2. Open the project folder in MATLAB.
3. Open the main Simulink model file.
4. Run the simulation to generate bandwidth allocation results.
5. (Optional) Enable the deep learning scheduling module to compare against the standard dynamic scheduler.

## Project Status

Research/simulation project — developed to study and compare bandwidth scheduling strategies in WCDMA networks.

## Author

Retro Lab
