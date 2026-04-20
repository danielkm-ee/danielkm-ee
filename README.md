# Daniel Monahan — danielkm-ee

**Electrical Engineer · RF & Analog Hardware · Embedded Systems**  
BS/MS Electrical Engineering & Physics @ Portland State University · GPA 3.89  
Portland, OR · [linkedin.com/in/danielkm-ee](https://linkedin.com/in/danielkm-ee) · dannym1432@gmail.com

---

I design hardware — from schematic to layout to bench bring-up. My focus is RF and mixed-signal PCB design, embedded firmware, and analog systems. I've done graduate-level research in neuromorphic machine learning and I care about the math and physics underneath the work, not just the tools on top.

Currently finishing a combined BS/MS at PSU and looking for roles in **RF/analog hardware design**, **embedded systems**, or **signal integrity** — particularly in defense, aerospace, semiconductor, or deep-tech environments.

---

## Featured Projects

### LoRa DAQ Node &nbsp;·&nbsp; [`lora_daq_module`](https://github.com/danielkm-ee/lora_daq_module)

> Wireless data acquisition node with 1 km sensor transmission range

![LoRa DAQ Node](https://raw.githubusercontent.com/danielkm-ee/lora_daq_module/main/docs/lora_daq_module_final_top.png)

Led a four-person team to design and build a LoRa-based wireless DAQ node from concept to validated hardware. Responsible for hardware architecture, component selection, full PCB layout, board bring-up, and rework. The board transmits I2C sensor data over 868–916 MHz to a base station at ranges exceeding 1 km.

**Hardware:** STM32 MCU · 16-bit ADC · I2C/UART expansion · MicroSD · USB-C with Li-ion charging · SMA RF interface  
**Stack:** C · STM32 HAL · KiCad · GNU/Linux

---

### DRA818V Walkie-Talkie &nbsp;·&nbsp; [`dra818v-walkie-talkie`](https://github.com/danielkm-ee/dra818v-walkie-talkie) &nbsp;*(WIP)*

> Compact VHF/UHF handheld transceiver — active design project

Hand-held transceiver design built around the Dorji DRA818V VHF/UHF module. Currently working through component selection and design specifications — active areas include audio front-end design, PTT logic, power management, and antenna matching. A project I'm using to deepen my applied RF design skills beyond coursework.

**Modules:** DRA818V transceiver · audio amp · PTT circuit · LiPo power  
**Tools:** KiCad · SPICE · Keysight ADS

---

### LiPo Battery Charger &nbsp;·&nbsp; [`lipo-charger`](https://github.com/danielkm-ee/lipo-charger)

> Single-cell Li-ion charger — analog power design fundamentals

![LiPo Charger PCB](https://raw.githubusercontent.com/danielkm-ee/usbc_lipo_charger/main/usbc_lipo_charger.png)

Single-cell lithium-ion battery charger PCB — a focused exercise in analog power circuit design, component selection for charging profiles, and PCB layout for thermal management. Starting point for the power architecture used in later projects.

**Tools:** KiCad · LTspice

---

### Trailrunners &nbsp;·&nbsp; [`trailrunners`](https://github.com/danielkm-ee/trailrunners)

> Reinforcement learning for spiking neural networks

Spiking neural network (SNN) research from my time at PSU's Teuscher Lab. Training neuromorphic RL agents to solve foraging tasks (Santa Fe Trail problem), with a focus on evaluating novel learning algorithms for SNN architectures. Related work contributed to a peer-reviewed publication in the 2024 Teuscher Lab Proceedings.

**Stack:** Python · PyTorch · PyGame

---

### 📡 Keysight ADS on Linux &nbsp;·&nbsp; [`install-ads-linux-demo`](https://github.com/danielkm-ee/install-ads-linux-demo)

> Step-by-step guide for running ADS on Linux — because it shouldn't be this hard

Practical walkthrough for getting Keysight ADS running on a Linux machine. Written because I couldn't find a clean guide when I needed one. If you're an RF engineer trying to do the same thing, this is for you.

---

## Skills

| Area | Details |
|---|---|
| **PCB Design** | Mixed-signal & RF layout, schematic capture, DFM, hand assembly & reflow, rework |
| **RF & Microwave** | VNA operation, TRL calibration, spectrum analysis, microwave circuit design |
| **Embedded Firmware** | Bare-metal C/C++, STM32 HAL, nRF SDK, UART/SPI/I2C, SWD debug |
| **EDA & Simulation** | KiCad, LTspice, SPICE, Keysight ADS, MATLAB |
| **ML Research** | PyTorch, spiking neural networks, reinforcement learning |
| **Languages** | C, C++, Python, AutoLISP, PowerShell |
| **Lab Instruments** | VNA, oscilloscope, spectrum analyzer, function generator |

---

## Publication

**Exploring Fractional Leaky Integrate-and-Fire Neurons in Spiking Neural Networks**  
Holden Lee, Daniel Monahan, Christof Teuscher  
*2024 Summer Proceedings, Teuscher Lab, Vol. 1, pp. 138–158 · Aug 2024*

Evaluated fractional-order neuron models as drop-in replacements for standard LIF neurons in SNNs, benchmarking accuracy and computational trade-offs on MNIST digit classification.

---

*Always open to interesting hardware problems. Reach out via [LinkedIn](https://linkedin.com/in/danielkm-ee) or email.*
