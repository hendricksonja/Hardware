
---

## 🧠 I. FOUNDATIONS OF COMPUTING HARDWARE

### 1. **Binary and Number Systems**

* Decimal, Binary, Hexadecimal, Octal: Conversions and practical uses
* Two’s Complement: Representation of signed numbers
* Binary arithmetic: Addition, overflow, carry


---

## 🔌 II. ELECTRICITY, TRANSISTORS, AND LOGIC GATES

### 1. **Electricity Basics**

* Voltage, current (amperage), and wattage
* DC vs. AC power, power supplies, Kill-A-Watt meter usage

### 2. **Transistors**

* BJT vs. MOSFET: symbols, components, behavior
* N-type and P-type doping, PN junctions
* MOSFETs as switches and analogies with capacitors

### 3. **Logic Gates and Circuits**

* AND, OR, XOR, NOT
* Truth tables
* Half and full adders
* Building 8-bit adders using logic gates


---

## 🧮 III. CPU AND MEMORY ARCHITECTURE

### 1. **CPU Components**

* ALU, control unit, registers
* Caches: L1, L2, L3 (location, speed, purpose)
* Instruction decoding, opcodes, operand processing

### 2. **Instruction Set Architecture (ISA)**

* Machine code vs. Assembly vs. High-level languages
* CISC vs. RISC (e.g., x86 vs ARM)

### 3. **Memory Hierarchy**

* Registers (SRAM)
* Cache (SRAM)
* Main Memory (DRAM)
* Storage (SSD, HDD)


---

## 🖥️ IV. MOTHERBOARDS AND BUS ARCHITECTURE

### 1. **Motherboard Components**

* Chipset (modern PCH vs old Northbridge/Southbridge)
* Power delivery (VRMs), sockets (LGA vs PGA), RAM slots, PCIe lanes

### 2. **Form Factors**

* ATX, microATX, MiniITX

### 3. **BIOS/UEFI**

* Boot process, CMOS battery, firmware storage


---

## 💾 V. MEMORY SYSTEMS

### 1. **Types of RAM**

* SRAM: Used in cache, registers
* DRAM: Used in main memory
* ECC vs non-ECC
* DRAM refresh cycles, soft vs hard errors

### 2. **SDRAM and DDR Generations**

* DDR → DDR2 → DDR3 → DDR4 → DDR5
* Speed ratings (e.g., DDR4-3200) and compatibility

### 3. **Memory Organization**

* Paging, memory matrix structure
* Address vs. data vs. control bus


---

## 📦 VI. STORAGE SYSTEMS

### 1. **HDDs**

* Platters, read/write heads, actuator arms, cache
* Seek time, latency, cylinder addressing
* Partitioning, formatting (low-level vs high-level), ZBR

### 2. **SSDs**

* NAND flash types: SLC, MLC, TLC, QLC
* 3D NAND, wear leveling, TRIM, page buffers
* Controllers and DRAM caches

### 3. **RAID**

* RAID 0, 1, 5, 6, 10 — advantages, redundancy, hot spares
* RAID efficiency formulas (`N-1`, `N-2`)


---

## 🎥 VII. VIDEO AND DISPLAY HARDWARE

### 1. **Display Technologies**

* CRT vs. LCD vs. OLED
* RGB pixel structure
* Resolutions and aspect ratios

### 2. **Signal Transmission Standards**

* VGA, DVI, HDMI, DisplayPort, USB-C, Thunderbolt
* HDBaseT and long-distance AV signaling

### 3. **Compression and HDR**

* Spatial vs. temporal compression
* Bit depth (8-bit vs 10-bit HDR10)


---

## 🔊 VIII. AUDIO SYSTEMS AND INPUT/OUTPUT

### 1. **Analog and Digital Audio**

* Sample rate (e.g., 44.1 kHz CD audio)
* Bit depth (16-bit vs 24-bit)
* Mono, stereo, surround, spatial audio (e.g., Dolby Atmos)

### 2. **Microphones and Speakers**

* Electromagnetic construction, resonance chambers
* Analog signal → digital sample chain

### 3. **USB and Serial Communication**

* USB versions, pinouts, color coding
* Differential signaling (D+ and D-), host polling
* Serial vs. parallel communication
* Full-duplex vs half-duplex vs simplex


---

## ⚡ IX. POWER SYSTEMS

### 1. **PSUs and Power Delivery**

* AC to DC conversion
* Rails: +12V, +5V, +3.3V
* ATX 24-pin connector, CPU 4/8-pin, Molex, SATA power

### 2. **Electrical Units**

* Voltage = pressure, current = flow, wattage = power
* Importance of grounding
* Modular vs. non-modular PSUs

### 3. **Safety and Quality**

* Kill-A-Watt meters, power supply testers
* Chip creep, surge protection, cheap PSU risks


---

## 🧠 X. SYSTEM DESIGN & ABSTRACTION

### 1. **Instruction Cycle**

* Fetch, decode, execute, write-back
* Role of registers, cache, and RAM in execution flow

### 2. **OS & Drivers**

* Abstraction layers: system calls, device drivers
* APIs: POSIX, Win32

### 3. **Abstraction Examples**

* Translation tables in SSDs vs NAT tables vs memory paging
* Benefits of hiding complexity (e.g., GUI over shell)


---

