# gnss-uav-spoofing-jamming
Practical implementation of GNSS spoofing and jamming attacks on UAVs using SDR and custom RF hardware.
# 🚁 GNSS Spoofing and Jamming on UAVs

A capstone research project demonstrating real-time GPS spoofing and jamming attacks on a custom-built drone platform using SDR and RF circuit design.

## 🔍 Objective
To analyze and expose the vulnerabilities in UAV GPS navigation systems by practically implementing spoofing (deception) and jamming (disruption) techniques using:

- HackRF One (SDR)
- Custom-built VCO-based RF jammer (designed in Altium)
- GNU Radio + gps-sdr-sim
- Cube Orange + Here3+ GPS + Skydroid T10

## 🛠️ System Architecture

- **Drone:** Custom quadcopter with Cube Orange FC, Here3+ GPS, Skydroid Tx/Rx
- **Jammer:** VCO + LMX1600 PLL + SGA6589Z amplifier circuit
- **Spoofer:** HackRF One + gps-sdr-sim, broadcasting forged GPS signals
- **Software:** Mission Planner, GNU Radio Companion, Altium Designer

## 🧪 Key Results

- **Jamming:** Disabled GPS lock mid-flight, rendering the drone non-operational
- **Spoofing:** Successfully changed GPS telemetry; drone interpreted false coordinates
- **Range:** Effective up to ~500-800 meters (ideal conditions)

## 📊 Highlights

- Designed RF jammer circuit from scratch using Altium
- Used GNU Radio and HackRF to simulate GPS spoofing
- Validated outcomes with Mission Planner telemetry
- Compared spoofing vs jamming impacts on navigation behavior

## 📁 Files Included
- `/docs` → paper, figures, photos
- `/hardware` → PCB designs, schematics
- `/software` → SDR flowgraphs and commands
- `/presentation` → summary decks (if any)

