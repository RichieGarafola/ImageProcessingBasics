
# Image Processing Basics with OpenCV

This project demonstrates foundational image processing techniques using **Python** and **OpenCV**. It's structured as a Jupyter notebook that walks through several common image tasks including reading image files, converting between color modes, and applying binary masks to selectively modify image regions.

> Project developed as part of coursework at **Capella University**  
> Ideal for beginners looking to understand practical computer vision with OpenCV.

---

## Features

- Read and inspect image metadata (resolution, color channels)
- Toggle between **color** and **greyscale** views
- Apply a **binary mask** to blackout specific areas of an image
- Save modified images for visual confirmation

---

## Project Structure

```bash
.
├── Assessment2_ImageProcessing.ipynb  # Main interactive notebook
├── sample_images/
│   ├── image-processing_color2greyscale_base.png
│   ├── image-processing_masking_base.jpg
│   └── image-processing_masking_mask.png
├── output/
│   └── section1_saved_image.png
│   └── section3_masked_output.png
├── requirements.txt
└── README.md
```

---

## Setup Instructions

1. **Clone the repository:**

```bash
git clone https://github.com/yourusername/image-processing-basics-opencv.git
cd image-processing-basics-opencv
```

2. **Install dependencies:**

```bash
pip install -r requirements.txt
```

Or manually install:

```bash
pip install opencv-python
```

3. **Run the notebook:**

```bash
jupyter notebook Assessment2_ImageProcessing.ipynb
```

---

## Visual Output Examples

### Section 1 – Original Image & Metadata
- Displays image resolution and channel count.
- Saves image to `/output/section1_saved_image.png`

### Section 2 – Greyscale Toggle Viewer  
- Interactive view that lets you switch between color and grayscale.
- Press `g` to toggle, any other key to exit.

### Section 3 – Binary Mask Application

```text
White pixels (255) in the mask will black out corresponding areas in the original image.
```

**Result Example:**

![Masked Output](output/section3_masked_output.png)

---

## Dependencies

- Python 3.8+
- opencv-python
- jupyter

Add this to `requirements.txt`:

```text
opencv-python
notebook
```

---

## Learning Objectives

This project introduces core OpenCV techniques:
- Image file I/O
- OpenCV’s GUI capabilities with keyboard input
- Color conversion (RGB to Grayscale)
- Applying masks using NumPy-style array logic
- Saving processed images

---

## Acknowledgements

- Developed as part of **CSC‑FPX4040** at Capella University
- Thanks to Capella faculty and course materials

---

## License

This project is for academic and educational use only.  
Attribution is appreciated if reused or modified.

---
