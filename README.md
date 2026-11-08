# DIY 8-Channel EEG Acquisition System

### Custom ADS1299 + ESP32-S3 Hardware for Brain-Computer Interface Research

A custom four-layer, eight-channel EEG acquisition PCB designed in KiCad to explore neural signal acquisition and motor-imagery-based brain-computer interfaces.

## Project Overview

This project focuses on designing EEG acquisition hardware from the component level, rather than relying on a commercial EEG development board.

The system is designed around the Texas Instruments ADS1299 analog front end and an ESP32-S3 microcontroller.

**Hardware features:**
- Eight EEG acquisition channels using the ADS1299
- ESP32-S3 microcontroller with SPI communication
- Custom positive and negative analog power supplies
- Electrode input filtering and protection
- USB-C connectivity
- microSD hardware interface for future data recording
- LIS3DH accelerometer for movement measurements
- Four-layer PCB with dedicated internal ground planes

## Engineering Work

Designed the schematic and PCB in KiCad, including component selection, power distribution, signal routing, input filtering, decoupling, and manufacturing documentation.

The project includes Gerber files, an assembly BOM, component placement information, and design source files.

## Current Status

**PCB design completed; professional fabrication and assembly review in progress.**

Hardware bring-up, firmware development, signal characterization, and motor-imagery experiments are planned next.

This design has not yet been validated through physical testing or evaluated for human electrical safety.

## Research Objectives

1. Validate ADS1299 communication and register configuration.
2. Acquire and analyze low-noise EEG signals.
3. Implement real-time sampling and data streaming.
4. Develop signal-processing and classification methods for motor imagery.
5. Explore EEG-based control of computer applications.

## Tools and Technologies

KiCad, ADS1299, ESP32-S3, SPI, analog circuit design, PCB layout, embedded systems, and digital signal processing.

## Safety

This is an experimental research prototype, not a certified medical device. Human-connected use requires appropriate electrical-safety evaluation, including isolation and electrode fault-current assessment.
