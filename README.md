# Gabriel Almeida

**Embedded Software Engineer · Portugal**

I work on embedded Linux devices and C/C++ firmware, along with the applications, diagnostics and automation that support them. I have around four years of professional software development experience, starting with roughly two years in full-stack development before moving into embedded systems.

Today, I focus on making systems easier to understand, debug and maintain. A recurring part of my work is building tools to investigate a problem, test hardware or automate a repetitive engineering task.

## What I do

I design, debug and maintain embedded systems used in retail environments. My work spans device communication, Linux userspace, event processing and the services and tools around the devices.

- **Firmware and concurrency:** I work with POSIX APIs, threads, synchronization and inter-process communication, investigating race conditions, deadlocks and memory safety issues.
- **RFID and hardware integration:** I work with RFID readers, LLRP and tag-processing pipelines, applying business logic to hardware events and forwarding results through MQTT or other interfaces.
- **Communication and networking:** I build and diagnose TCP/UDP socket communication, multicast, device discovery and serial interfaces, including RS485 and 1-Wire.
- **Embedded Linux delivery:** I work with Yocto builds, recipes, package dependencies and cross-compilation for ARM targets, including software updates and kernel or dependency compatibility investigations for legacy products.
- **Engineering tools and workflows:** I build desktop utilities, hardware test applications, monitoring and configuration tools, and maintain automated builds and release workflows.

My earlier full-stack work covered web applications, e-commerce, CRM systems and data processing. That background helps when a device needs to connect to a backend service, a user interface or a business workflow.

## How I work

I start by understanding the system and reproducing the failure where possible. When behaviour is unclear, I add instrumentation: targeted logs, a small diagnostic utility or measurements around a processing pipeline.

I use core dumps, stack traces, AddressSanitizer and tools such as `addr2line` to investigate crashes and memory corruption. For performance work, I measure event latency, CPU and wall-clock time, queue behaviour and synchronization overhead before deciding what to change.

I aim to keep fixes understandable and maintainable, automate repetitive work, and document the investigation, testing method and technical decisions so the next person can reuse them.

## Selected technologies

| Area | Technologies I work with |
| --- | --- |
| Primary | C, C++, Embedded Linux, Yocto, MQTT, LLRP, Linux networking, Git, Docker, Jenkins |
| Supporting software | Go, C#, Python, JavaScript, Bash, PowerShell, SQLite, GitHub Actions |
| Hardware and prototyping | ESP32, RFID systems, ARM embedded systems, electronics prototyping, FDM 3D printing, Fusion 360 |

I choose languages and tools according to the problem, whether that means firmware in C++, a Windows utility in C# or an automation script in Python.

## Personal engineering

Outside work, I build practical projects across software, electronics and mechanical design. I use FDM printing for functional parts, enclosures and assemblies, working with Fusion 360 and a Bambu Lab A1 to explore tolerances, materials and designs that can be manufactured reliably.

I also experiment with ESP32 devices, sensors, displays and custom controllers, alongside Linux servers, Docker, NAS systems, backups and Home Assistant.

## Current interests

- Making embedded event-processing systems more observable and predictable.
- Building diagnostic tools that shorten the path from a reported failure to a reproducible test.
- Connecting software, electronics and printed parts into useful everyday devices.
- Developing self-hosted services and home automation that are straightforward to maintain.

---

[GitHub](https://github.com/GabrielAlmd) · [Repositories](https://github.com/GabrielAlmd?tab=repositories)
