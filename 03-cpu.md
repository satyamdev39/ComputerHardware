# 03 — CPU & Instruction Execution

## 1. CPU

The Central Processing Unit executes instructions and performs operations required by software.

## 2. Instruction Cycle

A simplified model:

```text
Fetch → Decode → Execute → Write Back
```

Real processors are considerably more sophisticated and use techniques such as pipelining, out-of-order execution and speculative execution.

## 3. Core vs Thread

A **core** is a physical execution unit.

A **thread** is a unit of execution exposed by the processor/software model. Simultaneous multithreading can allow one physical core to maintain multiple hardware threads.

## 4. Clock Speed

Clock frequency indicates cycles per second, commonly expressed in GHz.

Higher GHz does **not** automatically mean a faster CPU because performance also depends on architecture, IPC, cache, workload, memory and other factors.

## 5. Cache

Typical hierarchy:

```text
Registers
   ↓
L1 Cache
   ↓
L2 Cache
   ↓
L3 Cache
   ↓
RAM
   ↓
Storage
```

Closer/faster storage is generally smaller and more expensive per unit of capacity.

## 6. MCQ

**Q1. What is a CPU core?**  
A. A physical execution unit  
B. A storage partition  
C. A cable  
D. A display connector

**Q2. What usually comes first in the simplified instruction cycle?**  
A. Execute  
B. Fetch  
C. Write back  
D. Shutdown

**Q3. Which is generally faster and smaller?**  
A. HDD  
B. RAM  
C. CPU cache  
D. External SSD

**Q4. Does a higher GHz always guarantee better CPU performance?**  
A. Yes  
B. No

### Answers
1. A  
2. B  
3. C  
4. B

## 🔬 Practical Task

Compare two CPUs and write five reasons why GHz alone is insufficient for choosing between them.
