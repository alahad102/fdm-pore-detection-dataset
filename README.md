# FDM Pore Detection Dataset

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Paper](https://img.shields.io/badge/Paper-WACV%202026-blue)](https://github.com/alahad102/fdm-pore-detection-dataset)

> **Annotated pixel-level pore segmentation dataset for Fused Deposition Modeling (FDM) 3D printing quality control**

This repository contains the first publicly available annotated dataset for pore detection in FDM 3D printed parts using continuous fiber-filled (CFF) biopolymer composites.

---

## 📊 Dataset Overview

- **Total Images:** 1,607
- **Total Annotated Pores:** 37,666
- **Format:** YOLO segmentation format (polygon annotations)
- **Material:** CFF/PBS composite
- **Printer:** QIDI Tech X-CF Pro
- **Printing Speed:** 40 mm/s

### Dataset Splits

| Split      | Images | Percentage |
|------------|--------|------------|
| Train      | 1,284  | 80%        |
| Validation | 161    | 10%        |
| Test       | 162    | 10%        |

---

---

## 📊 Dataset Statistics

### Pore Size Distribution
<img src="statistics/pore_size_distribution.pdf" width="600" />

- **Median Area:** 277 pixels²
- **Mean Area:** 504 pixels²
- **Range:** 1.5 – 7,889 pixels²
- **Small Pores (<300 px²):** 52%
- **Large Pores (>1000 px²):** 16%

### Pore Count Distribution
<img src="statistics/pore_histogram.pdf" width="600" />

### Dataset Split Comparison
<p float="left">
  <img src="statistics/split_histogram.pdf" width="400" />
  <img src="statistics/split_boxplot.pdf" width="400" />
</p>

The training, validation, and test splits are balanced with similar pore count distributions.
---

## 📥 Download

The dataset will be available for download soon. Please check back or contact the authors.

---

---

## 🖼️ Sample Images

### Raw Images (Camera Input)
<p float="left">
  <img src="examples/sample_1_raw.jpg" width="250" />
  <img src="examples/sample_2_raw.jpg" width="250" />
  <img src="examples/sample_3_raw.jpg" width="250" />
</p>

### Annotated Images (With Pore Segmentation)
<p float="left">
  <img src="examples/sample_1_annotated.jpg" width="250" />
  <img src="examples/sample_2_annotated.jpg" width="250" />
  <img src="examples/sample_3_annotated.jpg" width="250" />
</p>


## 🎓 Citation

If you use this dataset in your research, please cite our paper:
```bibtex

```

---

## 📄 License

This dataset is released under the MIT License. You are free to use it for research and commercial purposes. We only ask that you cite our paper.

---

## 📧 Contact

For questions about the dataset, please open an issue on this repository or contact the corresponding author.

---

## 🙏 Acknowledgments

This work was supported by the Air Force Office of Scientific Research (AFOSR).

---

**Last Updated:** December 2025
