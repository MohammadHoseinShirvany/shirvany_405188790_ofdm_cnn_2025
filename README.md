# shirvani_405188790_ofdm_cnn_2025

**Student:** Mohammad Hossein Shirvani (ID: 405188790)  
**Project:** Deep Learning-Based Channel Estimation with 1D CNN for OFDM Systems.  
**Reference:** Siriwanitpong et al., IEEE Access 2025 (DOI: 10.1109/ACCESS.2025.3531009).

## Project Overview
This repository contains a specialized implementation of channel estimation for OFDM systems in high-speed railway environments. We utilize a 1D Convolutional Neural Network (CNN) to achieve robust performance under high-mobility conditions.

- **Objective:** AI-driven channel estimation to overcome multipath fading.
- **Methodology:** 1D CNN architecture training on synthetic channel data.

## Implementation Guide
1. **Requirements:** Install dependencies via `pip install -r requirements.txt`.
2. **Run Experiment:** Execute `python run_project.py` to initiate the training and evaluation cycle.
3. **Core Logic:** The model architecture is defined in `ofdm_edu/model.py`, and the primary estimation logic is in `ofdm_edu/core.py`.
4. **Testing:** Unit tests are available in the `tests/` directory to verify the signal processing functions.
