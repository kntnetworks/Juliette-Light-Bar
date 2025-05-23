# Project Overview

<img align="left" height="200" src="https://github.com/user-attachments/assets/a8af49e5-cb96-4aa1-8689-702172a98a85"> This repository contains the KiCad design files for a replacement Printed Circuit Board (PCB) for the lighted band indicators in the ** *Juliette 5-Band, 18-Transistor Radio* **. The primary goal of this project is to replace the original band select PCB, which utilizes fuse style lamps, with 5mm LEDs and associated Current Limiting Resistors (CLRs).

I created this KiCad project for a restoration effort.  This Juliette radio contains a small PCB that is populated with fuse style lights, holders, and power connections from the band selection switch.  This provides a lighted band indicator on the bottom front of the radio. The radio under restoration 
suffered from leaking battery acid which had corroded the PCB to the point that it was not salvageable.  

## Getting Started

To view, modify, or fabricate this PCB, you will need to install [KiCad](https://www.kicad.org/), a free and open-source EDA suite.  

## Main Files 
- **Juliette Light Bar.kicad_sch** - this file is the schematic showing the symbols and electrical connections of the circuit. Note that mounting hole symbols are included in the schematic. Since mounting holes sometimes include copper pads for connectivity (e.g., circuit grounds) KiCad requires them to be added to the schematic so they can be placed as a footprint on the PCB.
- **Juliette Light Bar.kicad_pcb** - this is the PCB layout file that contains the component footprints including copper pads and traces.

Although this PCB can be exported and sent to a fab house for production, I have modified the footprints and traces with the goal of creating my own PCB at home with copper-clad board and the "toner-transfer" method of PCB creation.  

A great tutorial of this method can be found here:
https://www.youtube.com/embed/aemG_4sDz_Q?si=_ouqTl-AMnO7pNbh
