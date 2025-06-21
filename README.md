
# 🖼️ Image Processing Tasks in Python

This project contains four classic image processing operations implemented using Python and Jupyter Notebook.

## 📁 Project Structure

```
image_processing_project/
│
├── data/                         # Input images
│   └── input_image.jpg
│
├── notebooks/                    # Task notebooks
│   ├── task1_intensity_reduction.ipynb
│   ├── task2_spatial_average.ipynb
│   ├── task3_rotation.ipynb
│   └── task4_spatial_resolution_reduction.ipynb
│
├── outputs/                      # Generated output images
│   ├── task1/
│   ├── task2/
│   ├── task3/
│   └── task4/
│
├── requirements.txt              # Python dependencies
└── README.md                     # This file
```

---

## 🚀 Tasks Overview

### ✅ Task 1: Intensity Reduction
Reduce the number of gray levels in an image from 256 to any power of 2 (e.g., 2, 4, 8...).
- Input: grayscale image
- Output: intensity-quantized image

### ✅ Task 2: Spatial Averaging
Apply spatial average (smoothing) filters of sizes 3x3, 10x10, and 20x20.
- Works on both grayscale or color images
- Output: smoothed image with reduced local variance

### ✅ Task 3: Image Rotation
Rotate an image by:
- 45 degrees
- 90 degrees
- Output: rotated images with adjusted canvas size

### ✅ Task 4: Spatial Resolution Reduction (Block Averaging)
Apply non-overlapping block averaging (3x3, 5x5, 7x7).
- Works on color images
- Output: resolution-reduced effect by flattening color within blocks

---

## 🧪 How to Run

1. Clone or download this repo.
2. Place an input image inside the `data/` folder and name it `input_image.jpg`.
3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Open each notebook in `notebooks/` using Jupyter:
    ```bash
    jupyter notebook notebooks/
    ```

---

## 💾 Output

Processed images will be saved automatically to `outputs/` under the appropriate task folder.

---

## 👨‍💻 Dependencies

- Python 3.8+
- numpy
- pillow
- matplotlib
- opencv-python
- jupyter

---

## 📸 Example Preview (Optional)

