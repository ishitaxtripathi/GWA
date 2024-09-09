# GWA
### Extracting signals from a noisy time-series: Exploring gravitational-wave data: Gravitational Wave Detection Using Machine Learning and Quantum-Inspired Techniques

## Overview

This repository contains Jupyter notebooks and related files for the detection and classification of gravitational waves using various machine learning models. The study applies **Convolutional Neural Networks (CNNs)**, **Quantum-Inspired Neural Networks (QNNs)**, and **Bayesian optimization** to analyze gravitational wave signals from observatories like **LIGO** and **Virgo**. These approaches explore and enhance techniques for detecting gravitational wave events such as **GW150914**, **GW170817**, **GW190521**, and others.

## Repository Contents

| Filename         | Description                                                                                         |
|------------------|-----------------------------------------------------------------------------------------------------|
| `BOCNN.ipynb`    | Implementation of a Bayesian Optimized Convolutional Neural Network (CNN) for gravitational wave detection. |
| `BOINI.ipynb`    | Initialization and testing of Bayesian Optimization for improving CNN model performance.            |
| `BOQNN.ipynb`    | Bayesian Optimized Quantum-Inspired Neural Network (QNN) for handling complex gravitational wave data.|
| `GW150914.ipynb` | Analysis of the **GW150914** event using CNN-based detection methods.                                |
| `GW170817.ipynb` | Analysis of the **GW170817** neutron star merger, incorporating multi-messenger data analysis.       |
| `GW190521.ipynb` | Study of the **GW190521** intermediate-mass black hole merger, applying machine learning techniques.  |
| `GW200115.ipynb` | Detection and analysis of the **GW200115** black hole-neutron star merger.                           |
| `GW200129.ipynb` | Detailed analysis of the high-spin **GW200129** black hole merger.                                   |
| `GW_CCN_1D.ipynb`| Application of 1D Convolutional Neural Networks (CNNs) for detecting gravitational waves.            |
| `GW_CCN_2D.ipynb`| Application of 2D CNNs to analyze spectrograms for gravitational wave detection.                     |
| `Small.ipynb`    | A smaller dataset analysis focusing on 1,000 entries for rapid testing of quantum models.            |

## Models Used

1. **Bayesian Optimized CNN (BOCNN)**: Explores hyperparameter tuning using Bayesian optimization to improve the performance of CNNs.
2. **Bayesian Optimized Quantum-Inspired Neural Network (BOQNN)**: Integrates quantum-inspired models with machine learning to handle more complex datasets.
3. **1D/2D CNNs**: Applies both 1D and 2D CNN architectures to classify and detect gravitational wave signals from noisy data.
4. **Event-Specific Notebooks**: Custom models designed to detect specific gravitational wave events like GW150914, GW170817, etc.

## Key Gravitational Wave Events

The following notebooks focus on specific gravitational wave events:
- **GW150914**: The first detected gravitational wave, marking a historic discovery.
- **GW170817**: The first neutron star merger observed through gravitational waves.
- **GW190521**: A black hole merger within the intermediate-mass range, challenging traditional black hole formation theories.
- **GW200115**: Black hole-neutron star merger.
- **GW200129**: A high-spin black hole merger, providing insights into black hole dynamics.

