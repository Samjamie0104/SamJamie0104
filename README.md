<div align="center">

<img width="100%" src="./assets/header.svg" alt="Sam Topping — Embedded Systems & Electronics Engineer" />

<br>

<a href="https://www.sam-topping.co.uk">
<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=18&duration=3500&pause=1500&color=58A6FF&center=true&vCenter=true&repeat=true&width=650&height=35&lines=Firmware+from+bare+metal.+PCBs+from+schematic.+Systems+from+scratch.;Register-level+ARM+%26+RISC-V+%E2%80%94+no+HAL%2C+no+shortcuts;1kV+insulation+testing+%C2%B7+subsea+instrumentation+%C2%B7+6-layer+PCBs;Building+what+software+alone+can%27t." alt="Typing SVG" />
</a>

<br><br>

[![Portfolio](https://img.shields.io/badge/sam--topping.co.uk-58a6ff?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=0d1117)](https://www.sam-topping.co.uk)
&nbsp;&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-58a6ff?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d1117)](https://www.linkedin.com/in/sam-topping-768558229/)
&nbsp;&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-58a6ff?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117)](https://github.com/Samjamie0104)

</div>

<br>

---

```c
/* ════════════════════════════════════════════════════════════════════════
 *  SYSTEM INIT
 *  ──────────────────────────────────────────────────────────────────────
 *  Engineer    Sam Topping
 *  Education   MEng Electronic & Embedded Systems (First Class)
 *              Robert Gordon University · Aberdeen, Scotland
 *  Industry    Ashtead Technology — Subsea Instrumentation
 *  Domain      Hardware · Firmware · Power Electronics · PCB Design
 *  Focus       RTOS Development · HV PCB Design · Multimaster I2C
 * ════════════════════════════════════════════════════════════════════════ */

#define PHILOSOPHY "If the datasheet doesn't scare you, you haven't read it properly."
```

I design embedded systems from the PCB up — hardware, firmware, power electronics, and low-level software. My work spans bare-metal ARM and RISC-V development, high-voltage instrumentation, embedded communications, and production-oriented PCB design.

I specialise in systems that operate close to the hardware layer: register-level firmware, mixed-signal electronics, and robust embedded architectures designed for real-world deployment.

---

<div align="center">

## ⚡ Stack

<br>

**`Languages`**

![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![ARM Assembly](https://img.shields.io/badge/ARM_ASM-0091BD?style=for-the-badge)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

**`Hardware & Silicon`**

![STM32](https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white)
![RISC-V](https://img.shields.io/badge/RISC--V-283272?style=for-the-badge&logo=riscv&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=for-the-badge&logo=arduino&logoColor=white)
![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=for-the-badge&logo=kicad&logoColor=white)
![Embedded Linux](https://img.shields.io/badge/Embedded_Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

**`Domains`**

![Bare Metal](https://img.shields.io/badge/Bare_Metal-238636?style=for-the-badge)
![High Voltage](https://img.shields.io/badge/⚡_High_Voltage-da3633?style=for-the-badge)
![PCB Design](https://img.shields.io/badge/6--Layer_PCB-8957e5?style=for-the-badge)
![I2C](https://img.shields.io/badge/I2C-30363d?style=for-the-badge)
![SPI](https://img.shields.io/badge/SPI-30363d?style=for-the-badge)
![UART](https://img.shields.io/badge/UART-30363d?style=for-the-badge)

</div>

<br>

---

<br>

<div align="center">

## 🔬 Featured Projects

</div>

<br>

<table>
<tr>
<td width="50%" valign="top">

### ⚡ [High Voltage Cable Tester](https://www.sam-topping.co.uk/portfolio/high-voltage-automated-cable-tester-project)

**16-channel automated subsea cable qualification system**

`~1kV DC` `6-layer PCB` `Galvanic Isolation` `Precision Sensing`

Programmable high-voltage insulation testing with sub-microamp leakage measurement. Distributed microcontroller architecture with isolated sensing domains. Built for harsh industrial and subsea environments.

> *The kind of project where one wrong trace means smoke.*

</td>
<td width="50%" valign="top">

### 💡 [WCH CH32V003 WS2812](https://github.com/Samjamie0104/WCHCH32V003_WS2812)

**Bare-metal WS2812B driver · RISC-V · No HAL**

`Register-Level` `Sub-μs Timing` `Direct GPIO` `Zero Abstraction`

WS2812B demands 400ns/850ns timing precision. Built through direct register manipulation on a RISC-V core — no vendor HAL, no libraries. Every clock cycle accounted for.

> *When your timing budget is nanoseconds, there's no room for abstractions.*

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔐 [AES Encryption](https://github.com/Samjamie0104/AES_Encyryption)

**AES from first principles in C**

`Clean Room` `No Libraries` `CMake` `Modular Architecture`

Complete AES implementation without third-party crypto libraries. Every SubBytes, ShiftRows, and MixColumns operation written from scratch to understand encryption at the bit level.

> *Because "just use OpenSSL" doesn't teach you anything.*

</td>
<td width="50%" valign="top">

### 📡 [I2C Multimaster Sim](https://github.com/Samjamie0104/I2C_Multimaster_Simulations)

**Python simulation of I2C bus arbitration**

`Multimaster` `Arbitration Logic` `Bus Conflicts` `Protocol Analysis`

Full simulation of I2C multimaster arbitration — bus ownership, collision handling, and transaction-level timing. Validate embedded communication architectures before committing to silicon.

> *Simulate the bus fight before it happens on real hardware.*

</td>
</tr>
</table>

<details>
<summary><b>🔧 More Projects</b></summary>
<br>

### [Blackpill — STM32F411 Bare-Metal](https://github.com/Samjamie0104/blackpill)

Register-level STM32F411 development. Direct peripheral access — timers, DMA, GPIO — all through register manipulation. Understanding Cortex-M at the level the silicon intended.

`STM32F411` `DMA` `Timers` `Bare Metal`

</details>

<br>

---

<br>

<div align="center">

## 📊 Stats

<br>

<img width="49%" src="./assets/stats.svg" alt="Engineering Metrics" />
&nbsp;
<img width="49%" src="https://streak-stats.demolab.com/?user=Samjamie0104&theme=github-dark-blue&hide_border=true&background=0d1117&stroke=161b22&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff&sideLabels=8b949e&dates=6e7681" alt="GitHub Streak" />

<br><br>

<img width="98%" src="https://github-readme-activity-graph.vercel.app/graph?username=Samjamie0104&bg_color=0d1117&color=58a6ff&line=58a6ff&point=c9d1d9&area=true&area_color=58a6ff&hide_border=true&custom_title=Contribution%20Graph" alt="Activity Graph" />

</div>

<br>

---

<div align="center">

<br>

### Embedded systems engineered from silicon to software.

*If it runs on bare metal and handles real voltage, I'm interested.*

<br>

<img width="100%" src="./assets/footer.svg" alt="footer" />

</div>
