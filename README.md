# unit_proto_power_delivery_decoy_ch224k

## Overview
The **UNIT Power Board with Load Simulation** is a versatile power module designed for prototyping on breadboards. It is based on the **CH224** power management chip, supporting up to **100W** of output power. This module allows users to select different output voltages via a DIP switch, depending on the power adapter's supported protocol (PD, QC, or BC). Additionally, it features a **fixed 3.3V output** that can be enabled or disabled through the DIP switch.

## Features
- **Input:** USB-C (supports PD, QC, and BC protocols)
- **Selectable Output Voltages:** 5V, 9V, 12V, 15V, and 20V (via DIP switch)
- **Fixed Output:** 3.3V at 1.5A (toggleable via DIP switch)
- **Screw Terminal:** 5mm terminal providing VUSB output (5V-20V)
- **Breadboard Compatibility:** Fits both **54mm** and **64mm** wide breadboards
- **Voltage Rail Selectors:** Choose between 3.3V or VUSB for breadboard power rails

## DIP Switch Voltage Selection
The output voltage depends on the connected power adapter's supported protocol. The DIP switch settings determine the VUSB output voltage:

| S1 | S2 | S3 | VUSB Output |
|----|----|----|-------------|
| 0  | 0  | 0  | 5V          |
| 1  | 0  | 0  | 9V          |
| 0  | 1  | 0  | 12V         |
| 1  | 1  | 0  | 15V         |
| 0  | 0  | 1  | 20V         |

- **3.3V Enable Switch:** A separate switch enables or disables the fixed **3.3V** output.
- **Voltage Rail Selection:** Jumpers allow selecting **3.3V** or **VUSB** for each breadboard rail.

## Pinout
![UNIT Power Board Pinout](hardware/resources/protopowerdecoy_pinout_v1[EN].jpg)

## Usage
1. **Connect a USB-C power adapter** supporting PD, QC, or BC protocols.
2. **Set the DIP switch** to select the desired **VUSB output voltage**.
3. **Enable or disable the 3.3V output** if needed.
4. **Use the screw terminal** to access VUSB output externally.
5. **Set the rail voltage selectors** to supply either **3.3V or VUSB** to your breadboard power rails.

## Applications
- Prototyping with different voltage levels
- Powering breadboard circuits with variable voltage
- Simulating load conditions in power systems
- Developing USB-C powered projects

## License
This project is licensed under the **GPL-3.0 License**. See the LICENSE file for details.



