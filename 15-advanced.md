# 15 — Advanced Computer Hardware Concepts

## 1. PCIe Lanes

PCI Express uses lanes to provide scalable high-speed communication. A link can use configurations such as x1, x4, x8 or x16 depending on the platform/device.

## 2. NUMA

Non-Uniform Memory Access is an architecture where memory access cost can depend on which processor/node accesses which memory.

## 3. ECC Memory

Error-Correcting Code memory can detect and, depending on implementation, correct certain memory errors. It is important in systems where reliability is a priority.

## 4. Virtualization

Modern CPUs can provide hardware-assisted virtualization features that improve support for virtual machines.

## 5. IOMMU

An Input-Output Memory Management Unit can provide address translation and isolation for device memory access.

## 6. TPM

A Trusted Platform Module provides hardware-backed security functions such as key protection and measured boot support, depending on platform configuration.

## 7. Cache Coherence

In multicore systems, cache coherence mechanisms help keep multiple processor caches consistent with respect to shared memory.

## 8. MCQ

**Q1. PCIe x16 indicates:**  
A. A link configuration with up to 16 lanes  
B. 16 CPU cores  
C. 16 GB RAM  
D. 16 USB ports

**Q2. ECC memory focuses on:**  
A. Error detection/correction  
B. Graphics rendering  
C. Storage compression  
D. Display output

**Q3. IOMMU is associated with:**  
A. Device memory translation/isolation  
B. Monitor brightness  
C. Audio volume  
D. Keyboard layout

**Q4. TPM can provide:**  
A. Hardware-backed security functions  
B. Extra CPU cores  
C. More RAM capacity  
D. GPU rendering

### Answers
1. A  
2. A  
3. A  
4. A

## 🔬 Practical Task

Write a one-page explanation of how PCIe, CPU, RAM and an NVMe SSD cooperate when an application reads a file.
