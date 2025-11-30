# TLAAS Model: Adaxial-Abaxial Segmentation for Stacked Tobacco Leaves

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![MATLAB](https://img.shields.io/badge/MATLAB-R2022b-blue.svg)](https://www.mathworks.com/)

## Overview

This repository contains the source code for the **Tobacco Leaf Adaxial/Abaxial Surface Segmentation Model (TLAAS Model)**. 

This project addresses the challenge of feature extraction in stacked, post-cured tobacco leaf images. By leveraging an unsupervised strategy based on **Variance-Weighted S-V Channel Fusion**, the model effectively distinguishes between the **Adaxial (upper)** and **Abaxial (lower)** surfaces of tobacco leaves. This segmentation is a critical prerequisite for accurate stalk position classification and automated quality grading.

## Key Features

*   **Unsupervised Learning:** No need for large-scale pixel-level annotations.
*   **Robust Feature Fusion:** Dynamically weights Saturation (S) and Value (V) channels based on variance to capture photophysiological heterogeneity.
*   **Artifact Removal:** Integrated pre-processing to handle shadows, wrinkles, and stems.
*   **High Efficiency:** Lightweight computation suitable for industrial deployment.

## Repository Structure

*   `main.m`: The core MATLAB script for image processing and segmentation.
*   `Operating_Manual.md`: Detailed system requirements and usage guide.
*   `samples/`: A folder containing representative test images.
*   `results/`: Examples of segmentation outputs.

## Data Availability Statement

Due to commercial confidentiality and data privacy regulations regarding the industrial source of the samples, the full dataset used in the associated manuscript cannot be made publicly available. 

However, to ensure reproducibility and allow users to validate the algorithm, we have provided a **Representative Sample Dataset** in the `samples/` folder. These images cover typical scenarios found in the study and allow for full execution of the provided code.

## Getting Started

1.  Clone this repository.
2.  Open MATLAB.
3.  Navigate to the repository folder.
4.  Run `main.m` (Ensure a sample image path is specified).

For detailed instructions, please refer to the [Operating Manual](Operating_Manual.md).

## Citation

If you use this code or dataset in your research, please cite our paper:

> [Authors]. (2024). Adaxial-abaxial segmentation and feature extraction-driven position identification in stacked post-cured tobacco leaf images. *[Journal Name]*.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
