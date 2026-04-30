# 3-Level Automatic Light Control Circuit

## Overview
A Linear Circuit Analysis project that implements a tiered lighting system. The circuit automatically adjusts its output (Low, Medium, High) depending on the intensity of ambient light detected.

## Key Features
* **Multi-Stage Triggering:** Uses cascaded comparators to define three distinct light thresholds.
* **LDR Integration:** Real-time light sensing via a Light Dependent Resistor voltage divider network.
* **Analog Logic:** Built entirely with analog components (Op-Amps, Transistors, and Resistors) without a microcontroller.
* **Theoretical Analysis:** Verified through nodal analysis and Kirchhoff’s Laws to ensure accurate switching points.

## Hardware Components
* Op-Amps (LM741 or LM324)
* Light Dependent Resistor (LDR)
* Potentiometers (for threshold calibration)
* LEDs / DC Lamps
* Resistors & Transistors (as switches)

## How It Works
1. The LDR senses ambient light and changes resistance.
2. The voltage divider translates this into a variable voltage signal.
3. Comparators match the signal against pre-set reference levels.
4. Corresponding LEDs activate based on which threshold is crossed.
