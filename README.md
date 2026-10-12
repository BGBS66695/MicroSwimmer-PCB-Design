# MicroSwimmer PCB Design

## Overview

I designed this two-layer PCB in Autodesk Fusion 360 for a three-sphere robotic microswimmer. The board uses an ESP32-C3 microcontroller to generate PWM signals for two actuators.

An MT3608 DC-DC boost converter provides the required supply voltage, while an SN74AHCT125N buffer converts the 3.3V PWM signals to 5V.

## Design Highlight: Compact PCB Layout

The part I am most proud of is the compact layout. Since space is limited in the microswimmer, I wanted to keep the board as small as possible.

I adjusted the component placement several times to reduce unused space. Routing on both layers also helped me fit everything onto a smaller board without removing any necessary components.

The final layout is more compact than my initial design.
