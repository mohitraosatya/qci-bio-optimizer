# QCI-Bio-Optimizer: Nature-Inspired Circuit Optimization for Dual-Rail Qubits

This project implements a Genetic Algorithm (GA) to optimize quantum circuits designed for **QCI’s Dual-Rail Qubit architecture**. Built using Qiskit and simulated on Google Colab, the optimizer evolves gate parameters to preserve valid dual-rail logical encodings while reducing error-prone outputs — a step toward hardware-aware, fault-tolerant circuit design.

---

## Why This Matters for Quantum Circuits Inc.

Quantum Circuits Inc. is pioneering superconducting quantum systems with **built-in error detection and real-time feedback control** through its Dual-Rail Qubit (DRQ) design. However, **compiler-level optimization** tailored for these systems is still an open opportunity.

This project explores:

- ✅ **Error-aware compilation** using biological evolution principles (Genetic Algorithms)
- ✅ **Hardware-aligned circuit design** that respects dual-rail encoding integrity
- ✅ A scalable optimization framework that can adapt to noise, mid-circuit resets, and parity checks

By simulating logical qubit integrity and optimizing control gates in a GA loop, this project creates a proof-of-concept for a **bio-inspired, QCI-compatible transpiler or quantum compiler module**.

---

## 🧪 Project Highlights
- Simulates QCI-style **logical qubits using 4 physical qubits**
- Validates dual-rail encoding post-measurement for built-in error detection
- Optimizes RX/RY parameters using a **Genetic Algorithm**
- Tracks and evolves **fitness based on valid logical state probability**
- Built in Python using Qiskit and runs in Google Colab

---

## 📌 Future Work
- Integrate noise models and simulate thermal decoherence
- Extend to N-logical-qubit systems
- Incorporate QCI's real-time reset and feedback simulation
- Use Swarm Intelligence as a next-generation optimizer

---

> Inspired by evolution. Designed for fault-tolerant quantum hardware.
> Built with Quantum Circuits Inc.’s architecture in mind.
>
> Author: Satya Mohit Rao Kamkanampati
> Email: saka4331@colorado.edu
