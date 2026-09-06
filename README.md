# MP1584 Altium Designer Library

A professionally designed Altium Designer library for the **MP1584 3A, 1.5MHz, 28V Step-Down Converter** from Monolithic Power Systems (MPS).

This project was created as part of my ongoing work in **PCB Library Development, Schematic Symbol Creation, PCB Footprint Design, and Altium Designer Library Engineering**.

---

## Project Overview

The MP1584 is a high-frequency step-down switching regulator featuring an integrated high-side MOSFET.

According to the manufacturer documentation, the device supports:

* 4.5V to 28V operating input voltage
* Up to 3A output current
* Programmable switching frequency up to 1.5MHz
* Internal high-side MOSFET
* Current-mode control
* Thermally enhanced package

For complete electrical specifications and recommended operating conditions, please refer to the official manufacturer documentation.

---

## Library Contents

This repository contains:

### Schematic Symbols

Two schematic symbol variants were created for the MP1584.

The symbols are designed with emphasis on:

* Clear pin naming
* Correct pin numbering
* Logical pin grouping
* Power and signal pin identification
* Readable schematic presentation
* Compatibility with practical PCB design workflows

### PCB Footprints

Two PCB footprint variants were created based on the corresponding package/mechanical requirements.

The footprints include:

* Correct pad numbering
* Pad dimensions based on manufacturer documentation
* Component outline
* Pin-1 identification
* Courtyard
* Silkscreen
* Assembly-related geometry
* Thermal/Exposed Pad geometry where applicable

### 3D Model

A 3D representation is included for PCB visualization and mechanical verification.

---

## Design Process

The library was developed using the following workflow:

1. Manufacturer datasheet review
2. Pinout verification
3. Schematic symbol creation
4. Pin electrical type assignment
5. Footprint calculation and construction
6. Courtyard and silkscreen definition
7. Pin-1 identification
8. 3D model alignment
9. Visual inspection in Altium Designer
10. Library documentation

---

## Verification

The library was reviewed for:

* Pin numbering
* Pin names
* Symbol-to-footprint mapping
* Pad numbering
* Package dimensions
* Pin-1 orientation
* Silkscreen clearance
* Courtyard clearance
* 3D model alignment

Additional verification and manufacturing validation should be performed according to the requirements of the final PCB design and manufacturer.

---

## Repository Structure

```text
MP1584-Altium-Library/
│
├── Documentation/
├── Schematic/
├── Footprints/
├── 3D_Models/
├── Altium/
├── Source/
├── LICENSE
└── README.md
```

---

## Source

The electrical and mechanical information used to create this library was referenced from the official MP1584 documentation provided by **Monolithic Power Systems (MPS)**.

Official manufacturer:

https://www.monolithicpower.com/en/products/mp1584.html

---

## Disclaimer

This is an independently created Altium Designer library.

The MP1584 device, product name, trademarks, datasheet, and manufacturer-specific documentation remain the property of **Monolithic Power Systems, Inc. (MPS)**.

This repository is not affiliated with, sponsored by, or endorsed by MPS.

This project provides independently created CAD library data based on publicly available manufacturer documentation.

Always verify the library against the latest manufacturer documentation before using it in a production design.

---

## License

The original CAD/library files in this repository are provided under the license included in this repository.

Third-party trademarks, product names, datasheets, and manufacturer documentation remain the property of their respective owners.

---

## Author

**Ayoob Yazdani**

PCB Design | Altium Designer | PCB Library Development

GitHub: ayoobyazdani183-pcb


LinkedIn: www.linkedin.com/in/ayoob-yazdani-504127203

---

## Related Work

This project is part of an ongoing PCB Library Development portfolio focused on:

* Altium Designer
* Schematic Symbol Design
* PCB Footprint Design
* 3D PCB Models
* Component Library Engineering
* PCB Design
* Design Documentation
