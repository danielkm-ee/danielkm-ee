# Daniel Monahan — danielkm-ee

**Electrical Engineer · RF & Analog Hardware · Embedded Systems**  
BS/MS Electrical Engineering & Physics @ Portland State University · GPA 3.81  
Portland, OR · [linkedin.com/in/danielkm-ee](https://linkedin.com/in/danielkm-ee) · danielkm.rfeng@gmail.com

---

Could be described as an EE who likes to code. Always love a challenge and thrive on projects that bring a hazy hardware idea to a real, functioning, wave-shaping hardware solution. My desin process involves RF circuit design and simulations, layout, testing, validation, and rework; with a sprinkle of firmware development throughout -- especially while I wait for fabrication. Interested in projects involving audio, communications, antennas, and DSP; or any embedded design.

Currently finishing a combined BS/MS at PSU and looking for roles in **RF/analog hardware design**, **embedded systems**, or **signal integrity** — particularly in aerospace, semi-conductor, deep-tech or defense environments. Working towards skills in RFIC and ASIC design.

---

## Featured Projects

### LoRa DAQ Node &nbsp;·&nbsp; [`lora_daq_module`](https://github.com/danielkm-ee/lora_daq_module)

> Wireless data acquisition node with 1 km sensor transmission range

![LoRa DAQ Node](https://raw.githubusercontent.com/danielkm-ee/lora_daq_module/main/docs/lora_daq_module_final_top.png)

Led a five-person team to design and build a LoRa-based wireless DAQ node from concept to validated hardware in under 3 months. Responsible for hardware architecture, component selection, full PCB layout, board bring-up, and rework. The board transmits data from I2C devices or readings from the on-board ADC over 868–916 MHz to a base station at a 1km transmission range before any additional matching is added at the antenna.

**Hardware:** STM32 MCU (Seeed Studios Wio-E5) · 16-bit ADC · I2C/UART expansion · MicroSD · USB-C with Li-ion charging · 50-Ohm connector for a LoRa Antenna
**Stack:** C · STM32 HAL · KiCad · GNU/Linux

---

### Direct Conversion SDR &nbsp;·&nbsp; [`direct-conversion-sdr`](https://github.com/danielkm-ee/direct-conversion-sdr) &nbsp;*(WIP)*

> 2m homodyne phasing receiver for SSB and CW — active design project

Bluntly; 'an excuse to learn about sdr'. This is a personal project of mine started with the goals of managing IRR of I/Q signals, link budget, NF cascades, and DSP on a deeper level. Essentially to prove or bolster my abilities as a *real RF engineer*™. I have vendor s2p parameters selected for the 144MHz RF prefilter, LC branchline divider, LC wilkinson divider, and supports for the PGA-103+ in simulation, currently laying out test boards and designing my frequency conversion and baseband stages.

**Hardware:** STM32F4 · MC1496 Mixer · Si5351 Frequency Synth
**Tools:** KiCad · SPICE · Qucs-S · OpenEMS · GnuRadio or liquid-dsp (tbd)

---

### LiPo Battery Charger &nbsp;·&nbsp; [`lipo-charger`](https://github.com/danielkm-ee/lipo-charger)

> Single-cell Li-ion charger — analog power design fundamentals

![LiPo Charger PCB](https://raw.githubusercontent.com/danielkm-ee/usbc_lipo_charger/main/usbc_lipo_charger.png)

Single-cell lithium-ion battery charger PCB — an early exercise in power circuit design in KiCad, component selections for charging profiles, and PCB layout for thermal management. Serves as a reference design for other projects.

**Tools:** KiCad · LTspice

---

### Trailrunners &nbsp;·&nbsp; [`trailrunners`](https://github.com/danielkm-ee/trailrunners)

> Reinforcement learning for spiking neural networks

Spiking neural network (SNN) research from my time at PSU's Teuscher Lab. Training neuromorphic RL agents to solve foraging tasks (Santa Fe Trail problem), with a focus on evaluating novel learning algorithms for SNN architectures. Related work contributed to a peer-reviewed publication in the 2024 Teuscher Lab Proceedings.

**Stack:** Python · PyTorch · PyGame

---

### Keysight ADS on Linux &nbsp;·&nbsp; [`install-ads-linux-demo`](https://github.com/danielkm-ee/install-ads-linux-demo)

> Step-by-step guide for running ADS on Linux

Practical walkthrough for getting Keysight ADS running on a Linux machine, since I found the official instructions a bit more IT-oriented. Wrote this up while my classmates and I struggling through this install as part of our Microwave Circuit Design courses. It supplements the official licensing setup instructions and provides scripts and instructions on launching ADS as easily as any other desktop app -- for those who are less Linux-savvy or experienced users who could benefit from my `.desktop` and ADS launch script.

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
