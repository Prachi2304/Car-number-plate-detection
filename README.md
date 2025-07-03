#Vehicle Number Plate Detection using OpenCV
# 🚗 Vehicle Number Plate Detection using OpenCV & EasyOCR

This project focuses on detecting and recognizing vehicle number plates from static images using Python libraries such as OpenCV, EasyOCR, and Imutils. Built and executed on **Jupyter Notebook**, it demonstrates a simple yet effective implementation of number plate recognition for automation and surveillance systems.

---

## 🧠 Objective

To detect a number plate from a given vehicle image and extract the alphanumeric characters using image processing and OCR techniques.

---

## 🧩 Features

- ⚙️ **Image Preprocessing** (grayscale, noise reduction, edge detection)
- 🔍 **Contour Detection** for identifying license plate region
- 🖼️ **Plate Cropping** based on bounding contour
- 🔡 **Text Extraction** using EasyOCR
- ✅ Final visualization with bounding box and extracted text

---

## 🛠️ Tech Stack & Libraries

| Library         | Purpose                                     |
|-----------------|---------------------------------------------|
| `OpenCV`        | Image processing & visualization            |
| `EasyOCR`       | Optical Character Recognition (OCR)         |
| `Imutils`       | Helper functions for image transformation   |
| `Matplotlib`    | Display images in Jupyter Notebook          |
| `NumPy`         | Matrix operations and pixel manipulations   |
| `Torch`         | Backend requirement for EasyOCR             |

---

## 📥 Installation

Make sure you have Python 3.x and Jupyter Notebook set up. Then install the following packages:

```bash
pip install easyocr
pip install imutils
pip install opencv-python
pip install numpy==1.26.4
pip3 install torch torchvision torchaudio

