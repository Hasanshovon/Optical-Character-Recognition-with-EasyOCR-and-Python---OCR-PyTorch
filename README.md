# EasyOCR Project Documentation

This README outlines the steps to set up and run an Optical Character Recognition (OCR) project using EasyOCR, a Python library that simplifies the process of extracting text from images.
## output images
![output_1](https://github.com/Hasanshovon/Optical-Character-Recognition-with-EasyOCR-and-Python---OCR-PyTorch/assets/26182608/3923f4c9-54f7-4400-9f47-d4f3c58e03f8)
![output_2](https://github.com/Hasanshovon/Optical-Character-Recognition-with-EasyOCR-and-Python---OCR-PyTorch/assets/26182608/b8fb5895-cf54-4a9e-9fd8-276366488091)

## Prerequisites

Before you begin, ensure you have the following installed:
- Python 3.x
- Pip (Python package installer)
- An environment to run Python code (e.g., Jupyter Notebook, Python script, etc.)

## Installation

1. **Install PyTorch**: Visit [PyTorch's official website](https://pytorch.org/get-started/locally/) to find the installation command that matches your system's configuration. PyTorch is a deep learning library that EasyOCR depends on.

2. **Install EasyOCR**: Run the following command in your terminal or command prompt to install EasyOCR and its dependencies.

    ```bash
    pip install easyocr
    ```

    After installation, you should have EasyOCR along with its dependencies such as NumPy, scikit-image, Python-bidi, Pillow, torchvision, torch, OpenCV-Python, scipy, and others installed in your environment.

## Usage

### Import Dependencies

First, import the necessary libraries in your Python script or Jupyter Notebook.

```python
import easyocr
import cv2
from matplotlib import pyplot as plt
import numpy as np
