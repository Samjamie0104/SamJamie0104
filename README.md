<div align="center">

# Sam Topping
### Embedded Systems & Electronics Engineer

*First Class MEng · Robert Gordon University · Aberdeen, Scotland*

[![Portfolio](https://img.shields.io/badge/Portfolio-sam--topping.co.uk-0d1117?style=flat-square&logo=safari&logoColor=white&labelColor=21262d)](https://www.sam-topping.co.uk)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-sam--topping-0d1117?style=flat-square&logo=linkedin&logoColor=0A66C2&labelColor=21262d)](https://www.linkedin.com/in/sam-topping-768558229/)
[![GitHub](https://img.shields.io/badge/GitHub-Samjamie0104-0d1117?style=flat-square&logo=github&logoColor=white&labelColor=21262d)](https://github.com/Samjamie0104)

</div>

---

# About

I design embedded systems from the PCB up — hardware, firmware, power electronics, and low-level software.

My work spans bare-metal ARM and RISC-V development, high-voltage instrumentation, embedded communications, and production-oriented PCB design. I specialise in systems that operate close to the hardware layer: register-level firmware, mixed-signal electronics, and robust embedded architectures designed for real-world deployment.

Currently completing a First Class MEng in Electronic & Embedded Systems at Robert Gordon University, with industry experience developing subsea instrumentation systems at **Ashtead Technology**.

---

# Stack

## Languages

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![ARM Assembly](https://img.shields.io/badge/ARM_Assembly-0091BD?style=flat-square)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

---

## Hardware & Embedded

![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![RISC-V](https://img.shields.io/badge/RISC--V-283272?style=flat-square&logo=riscv&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=flat-square&logo=arduino&logoColor=white)
![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=flat-square&logo=kicad&logoColor=white)
![Bare Metal](https://img.shields.io/badge/Bare_Metal-success?style=flat-square)
![High Voltage](https://img.shields.io/badge/High_Voltage_PCB_%E2%9A%A1-critical?style=flat-square)
![Embedded Linux](https://img.shields.io/badge/Embedded_Linux-0d1117?style=flat-square&logo=linux&logoColor=FCC624)
![I2C](https://img.shields.io/badge/I2C-222222?style=flat-square)
![SPI](https://img.shields.io/badge/SPI-222222?style=flat-square)
![UART](https://img.shields.io/badge/UART-222222?style=flat-square)

---

# Selected Technical Capabilities

- 6-layer PCB design
- Register-level embedded firmware
- ARM Cortex-M development
- RISC-V bare-metal development
- High-voltage isolation design
- Mixed-signal embedded systems
- Oscilloscope & logic analyser debugging
- Embedded communication protocols (I2C, SPI, UART)
- Power electronics & precision sensing
- Embedded C/C++
- Python simulation & tooling
- Hardware fault analysis & debugging

---

# Featured Projects

## ⚡ [High Voltage Automated Cable Tester](https://www.sam-topping.co.uk/portfolio/high-voltage-automated-cable-tester-project)

> *16-channel automated subsea cable qualification system · ~1 kV DC · 6-layer PCB*

16-channel automated cable qualification system for subsea and industrial harnesses. Generates programmable ~1 kV DC insulation test voltages with precision leakage current sensing, automated continuity validation, isolated measurement domains, and onboard fault logging.

Designed around a distributed microcontroller architecture with galvanically isolated sensing stages and a 6-layer controlled-impedance PCB stackup intended for deployment within harsh industrial environments.

### Key Features
- ~1 kV DC insulation testing
- Automated continuity validation
- Distributed embedded architecture
- Precision current sensing
- Isolated high-voltage domains
- Industrial deployment considerations
- Subsea cable qualification workflow
- Embedded logging & diagnostics

---

## 💡 [WCHCH32V003_WS2812](https://github.com/Samjamie0104/WCHCH32V003_WS2812)

> *Bare-metal WS2812B driver on the CH32V003 · RISC-V · No HAL*

Bare-metal implementation of the WS2812B LED protocol on the CH32V003 RISC-V microcontroller using direct register manipulation and deterministic timing control.

The WS2812B protocol requires sub-microsecond timing accuracy. The driver was implemented without vendor abstraction layers, directly controlling GPIO timing at the hardware level.

### Technical Highlights
- Direct register-level GPIO control
- Deterministic timing implementation
- No vendor HAL usage
- RISC-V embedded development
- Timing-critical signal generation

---

## 🔐 [AES_Encryption](https://github.com/Samjamie0104/AES_Encyryption)

> *AES encryption implemented in C from scratch*

Clean-room AES implementation written entirely in C without third-party cryptographic libraries. Structured with modular source and test architecture using CMake-based builds.

Focused on understanding algorithm-level implementation details, memory handling, and low-level cryptographic operations.

### Technical Highlights
- AES implementation from first principles
- No external crypto libraries
- Modular C architecture
- CMake build system
- Unit testing structure

---

## 📡 [I2C_Multimaster_Simulations](https://github.com/Samjamie0104/I2C_Multimaster_Simulations)

> *Python simulation of multimaster I2C arbitration and bus behaviour*

Simulation environment for analysing I2C multimaster arbitration behaviour, bus ownership conflicts, and transaction-level communication behaviour before hardware implementation.

Used as part of ongoing research into multimaster embedded architectures and deterministic communication systems.

### Technical Highlights
- I2C arbitration modelling
- Multimaster bus simulation
- Timing behaviour analysis
- Protocol conflict handling
- Embedded systems research tooling

---

## 🔧 [blackpill](https://github.com/Samjamie0104/blackpill)

> *STM32F411 bare-metal embedded development*

Register-level STM32F411 development targeting deterministic peripheral control, direct memory access, timer configuration, and hardware-level debugging without abstraction layers.

Focused on understanding Cortex-M architecture beyond vendor frameworks.

### Technical Highlights
- STM32F411 development
- Direct peripheral access
- Bare-metal Cortex-M programming
- Timer & GPIO configuration
- Hardware-level debugging

---

# Engineering Interests

- Embedded firmware architecture
- Bare-metal ARM/RISC-V development
- High-voltage electronics
- Mixed-signal PCB design
- Real-time systems
- Hardware communication protocols
- Embedded Linux & edge compute
- Fault-tolerant embedded architectures
- Low-level optimisation
- Industrial instrumentation systems

---

# Current Focus

- Embedded operating system architecture and RTOS development on STM32
- Deterministic firmware design and low-level peripheral control
- High-speed embedded communications and multimaster I2C architectures
- Advanced PCB design for high-voltage and mixed-signal systems
- Hardware/software co-design for industrial embedded platforms

---

# Experience

## Ashtead Technology
### Embedded & Electronics Engineering Placement

Worked on subsea and industrial instrumentation systems within a real-world engineering environment, contributing to embedded electronics development, hardware integration, testing workflows, and engineering design activities.

Exposure included:
- Subsea instrumentation systems
- Embedded hardware integration
- Electronics testing & validation
- Engineering documentation
- Industrial deployment workflows
- Fault analysis and diagnostics

---

# Education

## Robert Gordon University
### MEng Electronic & Embedded Systems Engineering

- Predicted / Current Classification: **First Class**
- FastTrack integrated master's programme
- Focus areas include embedded systems, electronics, firmware, PCB design, digital systems, and communication architectures

---

<div align="center">

## Embedded systems engineered from silicon to software.

</div>
