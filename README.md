# Electromagnetic Skin Effect Simulation using COMSOL Multiphysics ⚡

This project investigates the electromagnetic skin effect in conductive materials using both theoretical analysis and numerical simulation in COMSOL Multiphysics.

The study analyzes how frequency, electrical conductivity, and magnetic permeability influence current density distribution and skin depth in conductors under alternating magnetic fields.

The project integrates electromagnetic theory with finite element simulation to provide a comprehensive understanding of high-frequency conductor behavior.

---

## 📦 Repository Contents

This repository contains the complete project materials:

### 📄 Technical Report

The full experimental and simulation report is provided:

```
report.pdf
```

The report includes:

- Electromagnetic theory background
- Skin depth theoretical derivation
- COMSOL modeling process
- Simulation results
- Frequency sweep analysis
- Material comparison between iron and copper

---

### 🧠 COMSOL Simulation Model

The COMSOL Multiphysics model file is included:

```
simulation/SkinEffectModel.mph
```

This file contains:

- Geometry model
- Material definitions
- Mesh configuration
- Frequency-domain solver
- Result visualization

The simulation uses finite element method to compute electromagnetic field and current density distributions.

---

## 🎯 Project Objectives

The main objective is to analyze the skin effect phenomenon in conductors.

Specifically:

- Investigate current density distribution at different frequencies
- Compare skin effect in different materials
- Validate theoretical skin depth using simulation

According to electromagnetic theory, the skin effect causes current to concentrate near the conductor surface at high frequencies.

This behavior is confirmed in the COMSOL simulation results.

---

## 🧪 Simulation Method

The simulation uses COMSOL Multiphysics electromagnetic module.

### Geometry

The model consists of:

- Conductive sphere
- Surrounding air domain

The air domain ensures accurate electromagnetic field propagation.

---

### Materials

Two materials are analyzed:

Iron:

- High magnetic permeability
- Strong skin effect

Copper:

- High electrical conductivity
- Larger skin depth

---

### Frequency Sweep

Simulations are performed at:

- 200 Hz
- 20 kHz
- 20 MHz

Results show increasing frequency leads to stronger skin effect.

---

## 📊 Key Findings

### Frequency Effect

Higher frequency results in:

- Stronger skin effect
- Shallower skin depth
- Surface current concentration

---

### Material Effect

Iron:

- Strong skin effect
- Smaller skin depth

Copper:

- Weaker skin effect at low frequency
- Strong skin effect at high frequency

---

### Theory Validation

Simulation results agree with theoretical skin depth equation:

δ = 1 / √(π f μ σ)

This confirms the accuracy of the simulation model.

---

## 🖥️ Software Requirements

COMSOL Multiphysics

Recommended version:

5.5 or later

Module required:

AC/DC Module

---

## 📁 Project Structure

```
Skin-Effect-COMSOL
│
├── README.md
│
├── report
│   └── Report.pdf
│
├── simulation
│   └── SkinEffectModel.mph
```

---

## ✨ Project Highlights

This project demonstrates:

Electromagnetic system modeling

Finite element simulation using COMSOL

Theoretical and numerical validation

Electromagnetic field analysis

High-frequency conductor behavior analysis

---

## 🚀 Summary

This project provides a complete electromagnetic analysis of the skin effect.

It combines:

Electromagnetic theory

Numerical simulation

Engineering modeling

The project demonstrates the practical application of finite element methods in electromagnetic engineering analysis.
