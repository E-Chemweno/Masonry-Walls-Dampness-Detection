# Masonry Dampness Detection

A Python script for visualizing dampness in masonry blocks using OpenCV.

## Overview

This project processes images of masonry blocks to detect and highlight areas affected by moisture. The script performs the following tasks:
- Loads images from specified folders
- Uses the first image as a reference
- Processes each image to calculate the relative damp area
- Generates grayscale, difference, thresholded, and opened images
- Creates heatmaps and overlay images to visualize damp areas
- Saves the processed images and results for further analysis

## Features

- Automated Image Loading
- Damp Area Calculation
- Heatmap Visualization
- Overlay Functionality

## Technologies Used

- Python
- OpenCV
- NumPy

## How to Use

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/Masonry-Dampness-Detection.git
