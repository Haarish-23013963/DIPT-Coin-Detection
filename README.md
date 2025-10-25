# DIPT-Coin Detection using OpenCV

## Introduction:
Coin detection is a common computer vision application that involves identifying round metallic disks in an image. This project uses thresholding, erosion, dilation, and blob detection to accurately detect coins.

## 🎯 Objective:
- Identify all coin objects in an image

 -Filter them based on circularity

- Display output with detected keypoints

- Count the total number of coins

## Libraries Used:
- OpenCV 

- NumPy

- Matplotlib

## Installation:
```python
pip install opencv-python numpy matplotlib

```

## Important Parameters Tuned:
```python
params.filterByCircularity = True
params.minCircularity = 0.8

params.filterByConvexity = True
params.minConvexity = 0.8

params.filterByInertia = True
params.minInertiaRatio = 0.8

```

These filters ensure only coin-shaped blobs are detected.
