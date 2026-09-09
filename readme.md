# High-Speed FPGA ADC/DAC Board

High-speed ADC/DAC expansion board for FPGA-based **signal acquisition, waveform generation, and digital signal processing**.

The board combines a **10-bit 50 MSPS ADC**, **10-bit 125 MSPS DAC**, OLED display, motion sensor, analog circuitry, and user controls.

Used with a compatible STEP FPGA core module, it supports a complete signal-processing path:

**Analog Input → ADC → FPGA Processing → DAC → Analog Output**

> **Note:** A compatible STEP FPGA core module is required.

---

## Features

* 10-bit 50 MSPS ADC
* 10-bit 125 MSPS DAC
* Parallel ADC/DAC interfaces
* 128 × 64 OLED display
* MMA7660FCR1 three-axis accelerometer
* High-speed comparator and operational amplifier
* Rotary encoder and push buttons
* Supports ADC → FPGA → DAC experiments
* Compatible with STEP FPGA core modules

---

## Hardware

### ADC

**3PA1030**

* 10-bit resolution
* Up to 50 MSPS
* Parallel digital interface

### DAC

**3PD5651E**

* 10-bit resolution
* Up to 125 MSPS
* Parallel digital interface

### Other Resources

* 128 × 64 OLED — SPI
* MMA7660FCR1 accelerometer — I2C
* TP1961-TR high-speed comparator
* TPH2501-TR operational amplifier
* Rotary encoder
* Push buttons

---

## Specifications

| Item                  | Specification          |
| --------------------- | ---------------------- |
| ADC                   | 3PA1030                |
| ADC Resolution        | 10-bit                 |
| ADC Sampling Rate     | Up to 50 MSPS          |
| DAC                   | 3PD5651E               |
| DAC Resolution        | 10-bit                 |
| DAC Update Rate       | Up to 125 MSPS         |
| ADC/DAC Interface     | Parallel data + clock  |
| Display               | 128 × 64 OLED          |
| Display Interface     | SPI                    |
| Motion Sensor         | MMA7660FCR1            |
| Sensor Interface      | I2C                    |
| Comparator            | TP1961-TR              |
| Operational Amplifier | TPH2501-TR             |
| Compatible Platform   | STEP FPGA core modules |

---

## Applications

* DDS signal generation
* Waveform generation
* Signal acquisition
* Digital filtering
* Frequency measurement
* ADC/DAC interface experiments
* FPGA digital signal processing
* Measurement and control projects

---

## Compatible FPGA Platforms

This board is designed for use with compatible **STEP FPGA core modules**.

The FPGA core module provides the programmable logic and signal-processing resources, while this board provides the ADC, DAC, display, sensor, controls, and analog interface circuitry.

> The FPGA core module is not included unless otherwise specified.

---

## Getting Started

1. Install a compatible STEP FPGA core module.
2. Create or open your FPGA project.
3. Configure the required ADC, DAC, or peripheral interfaces.
4. Compile and program the FPGA.
5. Acquire signals through the ADC or generate waveforms through the DAC.

---

## Notes

* Verify FPGA pin assignments and I/O voltage levels before use.
* ADC and DAC maximum sampling/update rates are device specifications and do not represent guaranteed end-to-end analog bandwidth.
* Basic FPGA and Verilog/VHDL experience is recommended.
