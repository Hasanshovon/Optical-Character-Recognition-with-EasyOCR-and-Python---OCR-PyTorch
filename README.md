# EasyOCR Project Documentation

This README outlines the steps to set up and run an Optical Character Recognition (OCR) project using EasyOCR, a Python library that simplifies the process of extracting text from images.

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
