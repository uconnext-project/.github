# uconnext

> Open aftermarket software platform for legacy Harman Uconnect 3C systems.

uconnext is a community-driven initiative focused on extending, modernizing and preserving legacy Uconnect infotainment systems used across FCA/Stellantis vehicles.

The project started as reverse engineering research targeting legacy Harman QNX-based head units and evolved into a broader platform for:

* custom software
* developer tooling
* system documentation
* recovery/update infrastructure
* aftermarket apps and integrations

---

# Current status

## Working

* custom update manifests
* runtime payload execution
* USB-based bootstrap environment

## Planned

* modular core framework (HMI replacement) (work in progress)
* DBus documentation
* Lua API documentation

---

# Philosophy

uconnext is not focused on piracy or malicious modification of vehicle systems.

The goal of the project is to:

* preserve aging infotainment hardware
* improve usability and performance
* enable community-driven development
* document undocumented systems
* provide an open development environment for legacy Uconnect platforms

In short:

> Make Uconnect Great Again

---

# Bootstrapper

The bootstrapper provides a non-persistent USB-based execution environment for research and development purposes.

Current research targets legacy Harman Uconnect 3C systems on SW versions 18.x.

Features:

* runtime payload execution
* USB-only operation
* no NAND modification required
* recovery-friendly workflow
* rapid iteration for reverse engineering

---

# Safety notice

This project is highly experimental.

Use at your own risk.

Unsupported modifications may permanently brick your device.

---

# Developer note

This project prioritizes experimentation, reverse engineering and rapid iteration over strict enterprise coding standards.

Some parts of the codebase may be partially AI-assisted to reduce development time and keep the focus on architecture, tooling and platform research.

---

# Long-term vision

The long-term goal of uconnext is to become an open aftermarket ecosystem for legacy Uconnect systems, including:

* custom apps
* themes/widgets
* open APIs
* tooling/documentation
* recovery/update systems
* community-driven development

---

# Credits

Huge thanks to:

* the XDA community
* reverse engineering researchers (especially Chris Valasek and Charlie Miller)
* everyone preserving weird embedded systems
