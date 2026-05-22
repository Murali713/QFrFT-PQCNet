# QFrFT-PQCNet

## A Hybrid Quantum-Classical Framework for Seismic Denoising Using Parameterized Quantum Circuits

This repository contains the implementation of the proposed **QFrFT-PQCNet** framework for adaptive seismic waveform denoising using a hybrid quantum-classical learning approach.

The framework integrates:

- Quantum Fractional Fourier Transform (QFrFT)
- Parameterized Quantum Circuits (PQC)
- Fractional-domain adaptive filtering
- Quantum-inspired unitary feature extraction
- Hybrid optimization using PennyLane and PyTorch

---

## Overview

Seismic denoising under non-stationary noise conditions remains a challenging problem because coherent seismic arrivals often overlap with broadband noise.

QFrFT-PQCNet addresses this challenge through:

- Learnable fractional Fourier representations
- Energy-preserving unitary transformations
- Adaptive fractional-domain filtering
- Quantum-inspired structured feature extraction


## Repository Structure

QFrFT-PQCNet/
│
├── README.md
├── requirements.txt
│
├── src/
│   └── qfrft_pqcnet.py
│
├── notebooks/
   └── QFrFT_PQCNet.ipynb
