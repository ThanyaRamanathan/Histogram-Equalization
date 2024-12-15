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
   git clone https://github.com/ThanyaRamanathan/Histogram-Equalization.git
2. Install dependancies:
   ```bash
   pip install -r requirements.txt

## Outputs
The outputs include:
- Enhanced images after histogram equalization.
- Side-by-side comparisons of original and processed images.
- Histograms for visual representation of pixel intensity distributions.

## Improvements
- Adaptive Equalization: Dynamically adjusts contrast for bright images.
- Brightness Preprocessing: Modifies brightness levels before applying equalization.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a branch for your feature/bugfix.
3. Submit a pull request.
