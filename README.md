# BatScan - Sonar Imaging

The BatScan project involved the design, implementation, and testing of an indoor sonar imaging system operating at 40kHz. 
The project involved signal processing in Julia to obtain a 1D range profile and 2D direction of arrival estimation as well as embedded software for a Teensy 3.6 microcontroller.

## Block Diagram

<img src="Diagrams/block_diagram.png" alt="Block diagram showing interaction of various modules in the sonar system." width="450"/>

## Signal Processing

<img src="Diagrams/signal_processing.png" alt="Overview of signal processing algorithm to produce 1D range profile." width="750"/>

## Embedded Software

### Transmitter

<img src="Diagrams/transmitter.png" alt="Transmitter chain including DAC and microcontroller." width="450"/>

### Receiver

<img src="Diagrams/receiver.png" alt="Receiver chain including ADC and microcontroller." width="450"/>

## Circuit Diagram

<img src="Diagrams/circuit_diagram.png" alt="Full circuit diagram." width="450"/>

## User Interface

<img src="Diagrams/user_interface.png" alt="User interface displaying 1D range profile." width="550"/>
