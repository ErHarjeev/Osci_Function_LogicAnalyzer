# Osci_Function_LogicAnalyzer
This project can work in 3 Modes. Oscilloscope, Function Generator and Logic Analyzer

**Statement of Purpose**

The aim of this project is to implement a system that is capable to works as signal generator , oscilloscope and logic analyzer.

**Hardware Requirements**

| **Component** | **Quantity** | **Schematic Symbols** |
| --- | --- | --- |
| Teensy 3.2 Board | 1 | U1 |
| SSD 1306 OLED | 1 | U2 |
| USB 5-pin Micro-B cable | 1 | - |
| Resistor (10 K ohm,1/4W) | 1 | R1 |
| Potentiometer (10 K ohm,1/4W) | 1 | RV1 |
| Tactile Button (TL1105F250Q) | 1 | B1 |
| Laptop / Desktop | 1 | - |

**Method**

**Hardware :**

This hardware is programmed and powered up by the USB Micro -B cable. When an USB cable is connected the Teensy 3.2, convert 5V of USB into 3.3V DC. This DC voltage is used to power up other circuitry. In schematic R1 as a pull up resistor. Though, in code we have used internal pullup resistor, but it a good practice of circuit design to use external one if possible. RV1 (potentiometer) is used give variable signal when the device is operation in oscilloscope. DAC pin is used to generate variable voltages that is used in signal generation e.g. sine wave, square wave, and triangular wave.

SSD 1306 is OLED, it is connected to the microcontroller by the I2C protocol.

**Note: Please refer Schematic in Media Folder**


**Code**

Its code is based on State Machine strategy. **Please refer State Machine Diagram in the Media folder.**

Code of this experiment (main.cpp) can be downloaded from this link

[https://github.com/ErHarjeev/Oszi\_FunGen\_LogicAnalyzer](https://github.com/ErHarjeev/Osci_Function_LogicAnalyzer)


**Youtube Link**

[https://www.youtube.com/watch?v=XRucpsSZX2s&feature=youtu.be](https://www.youtube.com/watch?v=XRucpsSZX2s&feature=youtu.be)


