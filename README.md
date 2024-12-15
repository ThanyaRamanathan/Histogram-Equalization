# Histogram Equalization

This project demonstrates the use of Histogram Equalization to enhance the contrast of images using both RGB and HSV channels. The repository provides scripts for processing, visualizing, and comparing the effects of histogram equalization on sample images.

## Features

- **Histogram Equalization (RGB)**: Adjusts pixel intensity values in each channel (Red, Green, Blue) to improve image contrast.
- **Histogram Equalization (HSV)**: Equalizes the Value channel while preserving Hue and Saturation, minimizing color distortion.
- **Visualizations**: Displays histograms before and after equalization for both RGB and HSV channels.
- **Adaptive Equalization**: Implements enhancements to address limitations of standard histogram equalization.

## Prerequisites

- Python 3.8 or higher
- Libraries: `numpy`, `matplotlib`, `opencv-python`

## Installation

1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <repository_directory>
