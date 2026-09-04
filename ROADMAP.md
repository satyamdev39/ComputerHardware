# 🗺️ Full Computer Hardware Learning Roadmap

## Phase 0 — Prerequisites

Learn:

- Basic electricity concepts: voltage, current, resistance, power
- Binary and hexadecimal basics
- Basic computer terminology
- Difference between hardware and software

**Checkpoint:** Explain what happens from pressing the power button to seeing the login screen.

---

## Phase 1 — Computer Fundamentals

Study:

- What is a computer?
- Input → Processing → Output → Storage
- Digital vs analog data
- Bits, bytes, KB/MB/GB/TB
- CPU, RAM, storage and motherboard roles
- Desktop vs laptop architecture

**Practical:** Identify the major components of a real computer.

---

## Phase 2 — Motherboard & Architecture

Study:

- Motherboard purpose
- CPU socket
- DIMM slots
- PCIe slots
- M.2 slots
- SATA connectors
- Chipset
- VRM
- CMOS battery
- Front-panel headers
- ATX and related form factors
- Buses and interconnects

**Practical:** Use a motherboard diagram and label every major connector.

---

## Phase 3 — CPU

Study:

- CPU architecture
- Core vs thread
- Clock frequency
- IPC
- Cache: L1/L2/L3
- Registers
- ALU and control unit
- Instruction cycle
- x86/x64 and ARM concepts
- CPU performance factors

**Practical:** Compare two CPUs using specifications rather than GHz alone.

---

## Phase 4 — RAM & Memory

Study:

- RAM purpose
- DRAM
- SRAM
- DDR generations
- DIMM vs SO-DIMM
- Capacity
- Frequency/data rate
- Latency
- Dual-channel operation
- Memory hierarchy
- Virtual memory

**Practical:** Inspect installed RAM information using your operating system.

---

## Phase 5 — Storage

Study:

- HDD
- SATA SSD
- NVMe SSD
- NAND flash
- SSD controller
- DRAM cache
- PCIe
- NVMe protocol
- Sequential vs random I/O
- TBW and endurance
- SMART concepts

**Practical:** Compare boot drive, game drive and archive drive requirements.

---

## Phase 6 — GPU

Study:

- Integrated vs discrete graphics
- GPU cores
- VRAM
- Graphics memory bandwidth
- Rasterization
- Rendering pipeline
- Display outputs
- GPU power requirements
- CPU/GPU bottlenecks

**Practical:** Determine whether a system is CPU-bound or GPU-bound in a hypothetical workload.

---

## Phase 7 — Power

Study:

- PSU role
- AC → DC conversion
- Wattage
- Efficiency
- Connectors
- 12V rail concepts
- PSU protection concepts
- VRM
- CPU/GPU power delivery

**Safety:** Do not open a PSU.

---

## Phase 8 — Cooling

Study:

- Heat generation
- Heat sink
- Thermal paste
- Air cooling
- Liquid cooling
- Fans and airflow
- Positive/negative/neutral pressure
- Thermal throttling
- Temperature monitoring

**Practical:** Design an airflow layout for a mid-tower PC.

---

## Phase 9 — I/O & Peripherals

Study:

- USB
- HDMI
- DisplayPort
- Ethernet
- Audio
- Bluetooth
- Wi-Fi
- Keyboard/mouse
- Webcams
- Printers
- External storage

**Practical:** Build a port-identification chart.

---

## Phase 10 — BIOS / UEFI / Firmware

Study:

- POST
- BIOS vs UEFI
- Boot process
- Secure Boot
- Boot order
- Firmware updates
- CMOS/UEFI settings
- Hardware detection

**Practical:** Enter your system firmware and identify CPU, RAM, storage and boot settings.

---

## Phase 11 — PC Assembly

Study:

1. Prepare workspace.
2. Install CPU.
3. Install RAM.
4. Install M.2 storage if applicable.
5. Install CPU cooler.
6. Install motherboard in case.
7. Install PSU.
8. Connect motherboard power.
9. Connect storage/GPU power.
10. Install GPU.
11. Connect front-panel headers.
12. Check cable routing.
13. Perform first boot.

**Checkpoint:** Explain every cable before connecting it.

---

## Phase 12 — Operating System ↔ Hardware

Study:

- Kernel
- Device drivers
- Interrupts
- DMA
- Device enumeration
- Memory management
- Processes and hardware resources
- Hardware abstraction

**Practical:** Use Device Manager or Linux hardware tools to inspect devices and drivers.

---

## Phase 13 — Troubleshooting

Master a systematic process:

```text
Observe symptom
      ↓
Define the problem
      ↓
Reproduce safely
      ↓
Check simplest causes
      ↓
Isolate component
      ↓
Test one variable at a time
      ↓
Repair / replace
      ↓
Verify
      ↓
Document
```

Common scenarios:

- No power
- No POST
- No display
- Random shutdown
- Overheating
- Slow storage
- RAM instability
- USB problems
- Network adapter problems
- Driver/device problems

---

## Phase 14 — Performance & Upgrades

Learn:

- Bottleneck analysis
- CPU upgrade planning
- GPU upgrade planning
- RAM capacity vs speed
- SSD upgrade planning
- PSU headroom
- Thermal constraints
- Compatibility
- Cost/performance analysis

**Project:** Create a balanced PC upgrade plan for a fixed budget.

---

## Phase 15 — Advanced

Explore:

- PCIe generations and lanes
- NUMA
- Cache coherence
- Memory controllers
- Virtualization extensions
- IOMMU
- ECC memory
- RAID concepts
- Hardware monitoring
- Firmware security
- TPM
- Hardware-assisted security
- Server hardware
- Embedded systems
- ARM vs x86 architecture

---

# 🏆 Capstone Projects

### Beginner
**Hardware Identification Guide**
- Photograph/diagram a PC.
- Label components.
- Explain each component's purpose.

### Intermediate
**PC Diagnostic Handbook**
- Create symptom → cause → test → solution decision trees.

### Advanced
**PC Build Engineering Report**
- Select CPU, motherboard, RAM, GPU, storage, PSU and cooling.
- Justify compatibility.
- Estimate bottlenecks and thermals.
- Document trade-offs.

### Expert
**Hardware Monitoring Dashboard**
Build a dashboard that reads available system telemetry and displays:
- CPU utilization
- Memory utilization
- Storage information
- Temperatures where supported
- GPU metrics where supported
