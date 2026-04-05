<!-- BAVIN'S README - BARE METAL ENGINEERING -->

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&pause=1000&color=00F794&center=true&vCenter=true&width=600&lines=Bare+Metal+%7C+Embedded+Systems+Engineer;C+%2F+Assembly+%7C+STM32+%7C+AVR;Hardware+%26+Software+Interface+Focus" />
</p>

---

## 🧠 About Me

Computer Engineering student focused on **low-level embedded systems development**.

I work close to the hardware — writing drivers, working with registers, and building systems from the ground up without relying on high-level abstractions.

My goal is to develop deep competence in:
- Microcontroller architecture
- Memory systems
- Peripheral interfacing
- Real-time systems
- Hardware/software co-design

---

## ⚙️ Core Engineering Focus

- Bare-metal programming (no abstraction layers)
- Register-level peripheral control
- Interrupt-driven and DMA-based systems
- Deterministic, real-time behavior
- Debugging using hardware tools (oscilloscope, logic analyzer, debugger)

---

## 🛠️ Tech Stack

### Languages
- C (primary)
- C++
- Assembly (ARM / AVR)

### Architectures
- AVR (ATmega328P)
- ARM Cortex-M (STM32F4 series)

### Protocols & Peripherals
- UART
- SPI
- I2C
- PWM
- DMA
- NVIC (interrupt system)

### Tools
- Git / GitHub
- STM32CubeIDE / GCC toolchain
- Debugging via SWD / JTAG
- Oscilloscope / Logic Analyzer

---

## 🧩 Assembly Knowledge

I use assembly to understand and control what happens beneath C code:

- Register-level operations (general-purpose & special registers)
- Stack operations and function call conventions (calling ABI)
- Interrupt entry/exit sequences
- Memory-mapped I/O access patterns
- Bit manipulation at the instruction level

Example (ARM Cortex-M style concept):
```asm
LDR R0, =0x40020014   ; Load GPIO register address
LDR R1, [R0]          ; Read register
ORR R1, R1, #1<<5     ; Set bit
STR R1, [R0]          ; Write back
