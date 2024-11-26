# Artificial Immune Systems (AIS) Models

This repository contains Python implementations of two Artificial Immune System (AIS) models: 

1. **Real-Valued Negative Selection Algorithm (RNSA)**
2. **Variable Negative Selection Algorithm (VD_NSA)**

AIS models are biologically inspired approaches for solving computational problems, particularly in anomaly detection, classification, and optimization.

---

## Table of Contents
- [Description](#description)
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [References](#references)
- [Contributions](#contributions)
- [License](#license)

---

## Description

### Real-Valued Negative Selection Algorithm (RNSA)
RNSA is designed for anomaly detection by generating detectors in a continuous space. Detectors represent patterns that are not present in the normal data, enabling the identification of anomalies. This implementation uses a Euclidean distance-based approach to validate and generate detectors in real-valued spaces.

### Variable Negative Selection Algorithm (VD_NSA)
VD_NSA extends traditional negative selection by allowing detectors of variable size. This enables the algorithm to adapt to the diversity of anomalies more effectively. Detectors are dynamically sized, improving detection performance and computational efficiency.

---

## Features

- **RNSA**:
  - Detector generation in continuous spaces.
  - Anomaly detection using Euclidean distance.
  
- **VD_NSA**:
  - Adaptive detectors with variable size.
  - Improved handling of diverse anomaly patterns.

---

## Getting Started

### Prerequisites
Ensure you have Python 3.6 or higher installed on your system. The required dependencies are:
- `numpy`
- `scipy`
- `scikit-learn`
- `matplotlib`

You can install them easily using the provided `requirements.txt` file.

```bash
pip install -r requirements.txt
