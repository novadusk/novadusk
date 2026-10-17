# novadusk

> *Building deterministic, reliable, and close-to-the-metal software.*  
> **Embedded Software & Linux Systems Engineer** — Focusing on **FreeRTOS / Embedded Systems**, **Linux Kernel Observability (eBPF)**, and **Industrial Edge Platforms**.

---

### 🛠️ Hardware & Systems Engineering Matrix

| Domain | Architectures, Stacks & Protocols |
| :--- | :--- |
| **Silicon & Architectures** | ARM Cortex-M (STM32F1/F4), Rockchip SoCs, x86_64 |
| **RTOS & Systems** | **FreeRTOS** (Task Scheduling, IPC, Queues, Timers), **Linux Kernel** (Memory Subsystem, Tracepoints) |
| **Peripherals & Protocols** | UART / DMA, SPI, I2C, CAN Bus, GPIO, IAP Bootloader (In-Application Programming) |
| **Languages** | C (C99 / C11), Modern C++ (C++14 / C++17), Python, Shell (Bash), ARM Assembly |
| **Toolchains & Tooling** | GCC / Clang, CMake, Make, GDB, OpenOCD, eBPF (BCC / bpftrace), Git |

---

### 📌 Selected Engineering Projects

#### 🔭 Linux Observability & Kernel Diagnostics
* **[MemScope-Guard](https://github.com/novadusk/MemScope-Guard)**  
  *Linux memory pressure and fragmentation evidence diagnostics with eBPF and Python.*  
  * Implemented non-invasive runtime observability for memory subsystem bottlenecks using eBPF tracepoints and kernel probes.
  * Captures memory compaction latency and allocation stalls with minimal overhead.

* **[linux-physical-memory-fragmentation-detector](https://github.com/novadusk/linux-physical-memory-fragmentation-detector)**  
  *Linux eBPF tools for observing physical memory fragmentation and external fragmentation.*  
  * Tracks buddy allocator behavior to detect external memory fragmentation issues causing latency spikes.

#### ⚡ Embedded & Real-Time Control
* **[stm32-freertos-range-hood-controller](https://github.com/novadusk/stm32-freertos-range-hood-controller)**  
  *STM32F103 & FreeRTOS real-time controller with motor PID, sensors, UART/DMA and IAP.*  
  * Multi-task architecture orchestrated by FreeRTOS with deterministic PID closed-loop motor control.  
  * Zero-copy packet reception using UART with circular DMA and custom IAP bootloader for fail-safe firmware updates.

#### 🤖 Industrial Robotics & Edge Platforms
* **[mine-inspection-platform-mimo](https://github.com/novadusk/mine-inspection-platform-mimo)**  
  *Mine multi-modal inspection robotic platform with edge perception and station dispatch.*  
  * Integrated multi-sensor perception with station dispatching pipelines and automated verification workflows.

---

### 📊 GitHub Activity & Language Distribution

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=novadusk&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="150" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=novadusk&layout=compact&theme=tokyonight&hide_border=true" height="150" alt="Top Languages" />
</div>

---

### 📫 Connect
* **GitHub**: [@novadusk](https://github.com/novadusk)
* **Specialization**: Embedded Firmware, RTOS, Linux Kernel Internals, eBPF Observability
