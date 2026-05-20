# Dual-Band Circularly Polarized UAV Antenna

## Corner Perturbation Enabled Dual Resonant Circularly Polarized Antenna for Resilient UAV Networks

A compact dual-band circularly polarized microstrip patch antenna designed for UAV communication systems operating at **2.4 GHz** and **5.2 GHz** frequency bands. The antenna uses **corner perturbation**, **U-slot loading**, and **stub optimization** to achieve dual-band operation, compact size, and circular polarization suitable for UAV telemetry, wireless communication, and real-time data transmission.

---

## Project Overview

Modern UAV systems require lightweight, compact, and reliable antennas capable of maintaining stable communication under dynamic flight conditions. Conventional antennas often suffer from:

- Polarization mismatch
- Limited bandwidth
- Large physical size
- Poor efficiency
- Unstable communication during UAV movement

This project proposes a **dual-band circularly polarized microstrip patch antenna** that addresses these challenges using:

- Corner truncation
- U-slot perturbation
- Partial ground plane
- Inset feed mechanism
- Defected Ground Structure (DGS)

The antenna is designed and optimized using **CST Microwave Studio** and fabricated on an **FR-4 substrate**.

---

# Features

- Dual-band operation at **2.4 GHz** and **5.2 GHz**
- Circular polarization at 5.2 GHz
- Compact low-profile structure
- Lightweight UAV-compatible design
- Good impedance matching
- Wide impedance bandwidth
- Easy PCB fabrication
- Suitable for UAV telemetry and wireless communication

---

# Antenna Specifications

| Parameter | Value |
|---|---|
| Operating Frequencies | 2.4 GHz & 5.2 GHz |
| Antenna Type | Microstrip Patch Antenna |
| Polarization | Circular Polarization |
| Substrate Material | FR-4 |
| Dielectric Constant | 4.4 |
| Substrate Thickness | 1.6 mm |
| Antenna Size | 48 × 39 × 1.6 mm³ |
| Feed Type | Inset Feed |
| Ground Structure | Partial Ground Plane |
| Simulation Tool | CST Microwave Studio |

---

# Antenna Geometry

The antenna consists of:

- Square radiating patch
- Corner truncation for circular polarization
- U-slot for dual-band resonance
- Stub loading for impedance matching
- Partial ground plane for bandwidth enhancement

---

# Design Parameters

| Parameter | Description | Value (mm) |
|---|---|---|
| W | Substrate Width | 48 |
| L | Substrate Length | 39 |
| GW | Ground Width | 31 |
| GL | Ground Length | 39 |
| RTR | Right Truncate | 4.59 |
| LTR | Left Truncate | 6 |
| LSTL | Left Stub Length | 7 |
| RSTL | Right Stub Length | 6 |
| LSTW | Left Stub Width | 4 |
| RSTW | Right Stub Width | 4 |
| SL | U-slot Length | 7.5 |
| SW | U-slot Width | 7 |
| IL | Inset Length | 6 |
| IW | Inset Width | 1 |
| FL | Feed Length | 12 |
| FW | Feed Width | 3.08 |

---

# Operating Principle

## 2.4 GHz Operation

The antenna operates in the fundamental **TM₁₀ mode**. The corner truncation breaks the degeneracy between TM₁₀ and TM₀₁ modes, helping generate circular polarization.

## 5.2 GHz Operation

The U-slot introduces an additional resonant current path, generating the second resonance at 5.2 GHz.

## Circular Polarization

Circular polarization is achieved through:

- Orthogonal mode excitation
- 90° phase difference
- Corner perturbation technique

---

# Simulation Results

## Return Loss (S11)

| Frequency | Return Loss |
|---|---|
| 2.4 GHz | -16 dB |
| 5.2 GHz | -29.8 dB |

---

## VSWR

| Frequency | VSWR |
|---|---|
| 2.4 GHz | 1.12 |
| 5.2 GHz | 1.53 |

---

## Bandwidth

| Frequency Band | Bandwidth |
|---|---|
| 2.4 GHz Band | 150 MHz |
| 5.2 GHz Band | 600 MHz |

---

## Radiation Efficiency

| Frequency | Efficiency |
|---|---|
| 2.4 GHz | 61.86% |
| 5.2 GHz | 50.94% |

---

## Axial Ratio

| Frequency | Axial Ratio |
|---|---|
| 2.4 GHz | 7.96 dB |
| 5.2 GHz | 2.11 dB |

Circular polarization is successfully achieved at **5.2 GHz**.

---

# Fabrication

The antenna was fabricated using standard PCB fabrication techniques on FR-4 substrate.

## Measurement Equipment

- Anritsu 20 GHz Vector Network Analyzer (VNA)
- SMA Connector
- CST Microwave Studio for simulation

---

# Measured Results

## Measured Return Loss

| Frequency | Measured S11 |
|---|---|
| 2.4 GHz | -11 dB |
| 5.2 GHz | -25 dB |

---

## Measured VSWR

| Frequency | VSWR |
|---|---|
| 2.4 GHz | 1.5 |
| 5.2 GHz | 1.8 |

The measured results closely match the simulated results.

---

# Applications

This antenna is suitable for:

- UAV telemetry systems
- UAV control links
- Real-time video transmission
- Smart agriculture
- Disaster management
- Border surveillance
- Environmental monitoring
- Emergency communication systems
- Infrastructure inspection
- Wireless communication systems

---

# Software Used

| Software | Purpose |
|---|---|
| CST Microwave Studio | Antenna Simulation |
| MATLAB | Graph Processing |
| VNA Software | Measurement Analysis |



