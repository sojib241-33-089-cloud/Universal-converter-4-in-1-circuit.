# Microcontroller-Based 4-in-1 Hybrid Power Converter System

![Circuit Diagram](hybrid_power_converter.png)

## Overview
This project presents a multi-stage **Unified 4-in-1 Hybrid Power Converter Architecture** controlled by a single Microcontroller (MCU). The system integrates four essential power electronic stages—AC-DC rectification, DC-DC buck conversion, DC-AC pure sine wave inversion, and AC-AC phase chopping—into a single modular setup.

Designed for smart grid integration, hybrid solar systems, and power electronics research, this setup replaces multiple standalone converters with a unified hardware topology and firmware-driven signal generation.

---

## Key Features
- **4 Conversion Stages in 1 System:** Handles AC-DC, DC-DC, DC-AC, and AC-AC conversions simultaneously.
- **Single MCU Orchestration:** Generates PWM, SPWM, SCR trigger, and TRIAC phase-cut signals from a single microcontroller.
- **Galvanic Isolation:** Uses optocouplers (MOC3021) and isolated gate drivers (IR2110) to protect digital control circuits from high-voltage transients.
- **Pure Sine Wave Output:** High-efficiency IGBT H-Bridge driven by SPWM with LC filtering for low THD AC load operation.
- **Automated Visualization:** Includes Python-Graphviz scripts to auto-generate system block diagrams and signal flow topologies.

---

## System Architecture & Topology
