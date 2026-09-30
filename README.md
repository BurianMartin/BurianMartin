# Martin Burian

**Embedded software engineer. I build systems from the metal up, and I finish them.**

I write C and C++ for the parts of a system most people treat as a black box:
boot code, kernels, drivers, real-time video pipelines, rendering engines.
When I want to understand something, I build it from scratch. When I start a
project, I scope it, ship it, and document it.

---

### ⚙️ What I do

- **Bare-metal & OS development:** my own kernel on the Raspberry Pi Zero W:
  scheduler, MMU, interrupts and drivers, written from scratch for ARMv6.
- **Embedded Linux:** cross-compilation, custom GStreamer builds with hardware
  (NVENC) encoding, deployment and debugging on vehicle computers in the field.
- **Low-latency video & networking:** RTSP streaming and teleoperation systems
  for autonomous vehicles, which is my day job.
- **Microcontrollers:** ESP32-S3 and Raspberry Pi Pico / RP2350, from
  peripheral drivers to a complete smartwatch OS.
- **Graphics:** a C++20 OpenGL engine with its own scene architecture,
  lighting model and resource system.
- **Security:** offensive-security background (Hack The Box CPTS path), so I
  build systems knowing how they get broken.

---

### 🚀 Things I've built

| Project | What it is |
|---|---|
| **[RaspberryPi-OS](https://github.com/BurianMartin/RaspberryPi-OS)** | A bare-metal operating system for the Pi Zero W (BCM2835). No Linux, no libraries: scheduling, memory management with the MMU, interrupts and drivers, all mine. |
| **[ESP32_S3_SmartWatch](https://github.com/BurianMartin/ESP32_S3_SmartWatch)** | A complete smartwatch OS for the LilyGO T-Watch S3. Started as my bachelor's thesis, still growing. |
| **[OpenGL-Renderer (Forge)](https://github.com/BurianMartin/OpenGL-Renderer)** | A C++20 real-time engine: Engine → Scene → Layer architecture, Blinn-Phong multi-light, multi-camera split-screen, skyboxes, a deduplicating resource cache. |

---

### 🛠️ Toolbox

- **Languages:** C · C++ (17/20) · ARM assembly · Python · CMake
- **Platforms:** Raspberry Pi (bare metal & Linux) · RP2040/RP2350 · ESP32-S3 · x86 Linux
- **Systems:** Linux kernel & device tree · GStreamer · NVENC · OpenGL · FreeRTOS · Git · CI
- **Hardware:** logic analyzers · UART/SPI/I2C · JTAG/SWD debugging

---

### 🧭 How I work

- **I'm not scared of big projects.** An OS, an engine, a smartwatch platform:
  I break big things into milestones and ship them.
- **I build to understand.** Writing it from scratch once is the fastest way
  to really know how it works.
- **Scope, roadmap, done.** My projects have a `SCOPE.md` and a `ROADMAP.md`,
  and a finish line.

---

### 🔭 Currently

Building a series of Raspberry Pi projects: a pocket CHIP-8 console, a Pico
logic analyzer, an ISS pointer and an OTA update system for embedded Linux.

🎓 MSc studies at FIT VUT (Brno University of Technology) · Bc., VŠB – Technical University of Ostrava<br>
📍 Czech Republic
