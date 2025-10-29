
# PMBus Summary

## Power Management Bus

- I2C based Communication standard for "power supply management".

- Owned and regulated by:
    - The System Management Interface Forum (SMIF).
    - Open to all membership - Specification are available for everyone.

- Works with all type of power management products:
    <details>
    <summary> AC-DC power supllies </summary>

## Overview

An AC–DC power supply is an electronic device that converts alternating current (AC) from the mains (like 230 V, 50 Hz in India) into direct current (DC) required by most electronic circuits and digital devices.
It’s also called a rectifier power supply or adapter.

## ⚙️ Key Stages of Conversion

Step-down Transformer

Reduces high AC voltage (e.g., 230 V) to a lower level (e.g., 12 V or 24 V AC).

Some modern supplies use “switch-mode” techniques without transformers.

Rectifier Circuit

Converts AC to pulsating DC using diodes.

Common types: Half-wave, Full-wave, or Bridge rectifier.

Filter Circuit

Smooths out the pulsating DC using capacitors or inductors.

Voltage Regulator

Maintains a stable DC output despite fluctuations in load or input voltage.

Examples: Linear regulators (e.g., LM7805) or Switching regulators (SMPS).

## ⚡ Types

Linear Power Supply

Simple design, uses transformer and linear regulators.

Advantages: Low noise, stable.

Disadvantages: Heavy and less efficient.

Switch-Mode Power Supply (SMPS)

Uses high-frequency switching for voltage conversion.

Advantages: Lightweight, efficient, compact.

Disadvantages: Can produce switching noise.

## 🏭 Real-Life Examples
Device	Application	Output Voltage
Laptop Adapter	Converts 230 V AC → 19 V DC	19 V
Mobile Charger	Converts 230 V AC → 5 V DC (USB)	5 V
Desktop SMPS	Converts 230 V AC → 12 V, 5 V, 3.3 V DC	Multiple
LED Bulb Driver	Converts 230 V AC → ~60 V DC	60 V
Industrial PLC Power Supply	Converts 230 V AC → 24 V DC	24 V
## 🔍 Summary

Converts AC to DC for electronic circuits.

Key parts: Transformer → Rectifier → Filter → Regulator.

Used everywhere — from chargers and computers to industrial equipment.

Modern systems prefer SMPS for better efficiency and compactness.
</details>
 
