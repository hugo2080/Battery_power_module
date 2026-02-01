# Battery_power_module

![Project Status](https://img.shields.io/badge/Hardware-CERN--OHL--1.2-blue.svg)

Battery power module for bathroom scale

Place a 0.7 V forward voltage rectifier diode, e.g. 1N4007, between pin 2 of connector J2 and VDD of the MCU board, with the anode facing J2, to reduce the voltage to a safe 3.6 V.

## Licensing

This project is released under the **CERN Open Hardware Licence v1.2**.

* **Hardware Documentation:** Licensed under the terms of CERN OHL v.1.2. See `cern_ohl_v_1_2.txt` for the full license text.
* **Software/Firmware (if applicable):** none.
* **Documentation Location:** https://github.com/hugo2080/Battery_power_module

> **Note:** As per the license requirements, any redistribution or modification of this project must retain the original copyright notices and the license text.

## Repository Structure

Based on the project configuration, the files are organized as follows:

* `/hardware` – KiCad source files (`.kicad_sch`, `.kicad_pcb`).
* `/datasheets` – Placeholder for component datasheets (this folder is empty due to manufacturer copyrights; please download them manually for your own use).
* `/software` – Firmware source code and scripts.
* `CHANGES.TXT` – A log of modifications (required by CERN OHL).
* `PRODUCT.TXT` – Contact information for the author and potential manufacturers.

## Technical Requirements

* **PCB Design:** KiCad (version 9.0 or newer recommended).
* **Firmware/Software:** none.

## Getting Started

1.  **Clone the repository:** `git clone https://github.com/hugo2080/Battery_power_module`
2.  **Open the hardware project:** Navigate to the `/hardware` folder and open the `.kicad_pro` file in KiCad.
3.  **Prepare for assembly:** Refer to the Bill of Materials (BOM) and download the necessary datasheets into the `/datasheets` folder.

## Disclaimer

This documentation is distributed **WITHOUT ANY EXPRESS OR IMPLIED WARRANTY**, including of merchantability, satisfactory quality, and fitness for a particular purpose. Use this hardware at your own risk. Please see the CERN OHL v.1.2 for applicable conditions.

---
Copyright hugo2080 2025