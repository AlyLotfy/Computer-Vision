# Computer Vision — AAST Coursework

**Lab work and assignments from the Computer Vision course at AAST College of Artificial Intelligence.**

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?logo=python&logoColor=white)](#)
[![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=white)](#)
[![Notebook](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)](#)

---

## Overview

This repository collects hands-on implementations of foundational computer-vision techniques covered in AAST's Computer Vision course. The focus is on understanding what's happening **under the hood** — implementing classical CV algorithms from primitives rather than just calling library functions.

---

## Contents

| Notebook | Topics |
| --- | --- |
| `CV-Lab 6DCT-SIFT.ipynb` | **Discrete Cosine Transform** for compression-style frequency-domain analysis · **SIFT** (Scale-Invariant Feature Transform) for keypoint detection and matching |
| `Lab7.ipynb` | Continuation of feature-detection / matching pipeline |

---

## What's Covered

### Discrete Cosine Transform (DCT)
- Forward and inverse DCT on image patches
- Coefficient quantization (the basis of JPEG compression)
- Reconstruction quality vs. compression-ratio trade-off

### SIFT — Scale-Invariant Feature Transform
- Scale-space construction via Gaussian pyramids
- Keypoint detection (DoG extrema)
- Orientation assignment and descriptor extraction
- Cross-image keypoint matching

These are the same building blocks used in modern visual SLAM, image stitching, and (until learned features took over) object recognition.

---

## Tech Stack

- **Python 3.10+**
- **OpenCV** — reference implementations and visualisation
- **NumPy** — core math
- **Matplotlib** — plotting
- **Jupyter Notebook**

---

## Quick Start

```bash
git clone https://github.com/AlyLotfy/Computer-Vision.git
cd Computer-Vision

pip install opencv-python numpy matplotlib jupyter
jupyter notebook
```

---

## Related

Computer-vision techniques used in production form the back-half of my graduation project's face-recognition login flow — see [Pepper Medical Assistance Robot](https://github.com/AlyLotfy/Pepper-Medical-Assistance-Robot).

---

## License

Academic coursework, AAST College of Artificial Intelligence.
