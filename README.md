# DC-DC Boost Converter (IRF540N)

## Overview
This project demonstrates the design, simulation, and hardware implementation of a DC-DC Boost Converter using the IRF540N MOSFET. The converter is designed to step up a lower input voltage to a higher output voltage. The project includes simulation results and the final hardware setup.

## Objectives
- Design a boost converter using IRF540N MOSFET.
- Achieve a higher output voltage from a lower input voltage.
- Verify the performance through simulation and hardware testing.

## Components Used
- **IRF540N**: N-channel MOSFET for switching
- **Inductor**: Stores energy during switching cycles
- **Diode**: Ensures proper current flow
- **Capacitor**: Smooths the output voltage
- **Resistor**: Loads the converter
- **Veroboard**: For assembling the circuit
- **Oscilloscope**: Measures the output waveform
- **DC Power Supply**: Provides input voltage
- **Multimeter**: Measures the output parameters

## Software Tools
- **Proteus**: Used for circuit simulation and analysis

## Key Features of IRF540N
- Drain-Source Voltage: 100V
- Continuous Drain Current: 33A
- Rds(on): 44mΩ at Vgs = 10V
- Power Dissipation: 130W

## Circuit Diagram
The boost converter circuit includes key components like the MOSFET, inductor, diode, and capacitor, arranged to step up the input voltage to a higher output voltage.

## Results
| Duty Cycle | Input Voltage | Calculated Output Voltage | Measured Output Voltage |
|------------|---------------|---------------------------|-------------------------|
| 0.1        | 5V            | 5.5V                      | 4.8V                    |
| 0.2        | 5V            | 6.2V                      | 5.6V                    |
| 0.3        | 5V            | 7.1V                      | 6.2V                    |

## Applications
- Battery-powered devices
- Renewable energy systems
- Voltage step-up scenarios

## License
This project is licensed under the MIT License.
