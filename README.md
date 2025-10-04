# 2025-2026-BT-Segmentation-UEL-Dissertation-Project
Project Title: 

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

## 🎯 Project Overview

Medical deep learning project for brain tumor classification and segmentation using MRI scans.

## 📁 Dataset

- **Source**: [BraTS, Kaggle, etc.]
- **Size**: X GB, Y images
- **Classes**: Glioma, Meningioma, Pituitary, No Tumor

## 🚀 Quick Start

```bash
# Clone repository
git clone https://github.com/yourusername/brain-tumor-dl-project
cd brain-tumor-dl-project

# Setup environment
conda env create -f environment.yml
conda activate brain-tumor-dl

# Run training
python src/models/train.py --config configs/training.yaml
