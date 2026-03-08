# MADDRNet: Synergizing VFM with Morphology-Aware Dual-Domain Resonance Network for Remote Sensing Change Detection

[![Paper](https://img.shields.io/badge/Paper-Coming_Soon-blue.svg)](URL_TO_YOUR_PAPER)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Official PyTorch implementation of **MADDRNet**.


## 👁️ Qualitative Results
Extensive experiments on four benchmark datasets (CLCD, GFSW-CLCD, LuojiaSET, and Water-CD) demonstrate that MADDRNet achieves state-of-the-art (SOTA) performance, showing excellent ability in preserving target morphology while suppressing climate-induced noise.

### 1. Results on CLCD Dataset
<p align="center">
  <img src="./images/clcd.png" alt="CLCD Results" width="100%">
</p>

### 2. Results on GFSW-CLCD Dataset
<p align="center">
  <img src="./images/gfswclcd.png" alt="GFSW-CLCD Results" width="100%">
</p>

### 3. Results on LuojiaSET Dataset
<p align="center">
  <img src="./images/luojia.png" alt="LuojiaSET Results" width="100%">
</p>

### 4. Results on Water-CD Dataset
<p align="center">
  <img src="./images/water.png" alt="Water-CD Results" width="100%">
</p>

*(Note: Red areas denote false positives, green areas denote false negatives, and white areas represent true positive changes.)*

---

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- PyTorch 1.12.0+ (or compatible versions)
- CUDA 11.6+

### Installation
```bash
git clone [https://github.com/wk448379-source/weihanming.git](https://github.com/wk448379-source/weihanming.git)
cd MADDRNet
pip install -r requirements.txt
