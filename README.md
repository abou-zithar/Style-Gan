# Style Transfer with TensorFlow

This repository contains code for performing arbitrary style transfer using TensorFlow. Arbitrary style transfer refers to transferring the artistic style of one image (style image) to the content of another image (content image), resulting in a new image that combines the content of the content image with the style image.

## Overview

The code provided in this repository demonstrates how to implement arbitrary style transfer using a pre-trained VGG19 model in TensorFlow. It includes:

- A `StyleTransferNetwork` class for setting up the style transfer network, extracting features, and computing loss.
- Functions for scaling images and loading content/style images.
- Example usage of the `StyleTransferNetwork` class to reconstruct content, reconstruct style, and perform style transfer.

## Prerequisites

- Python 3
- TensorFlow
- TensorFlow Datasets
- NumPy
- Matplotlib
- PIL (Python Imaging Library)

## Usage

1. Run the Jupyter notebook `ch5_arbitrary_style_transfer.ipynb` to see examples of arbitrary style transfer using the provided code.

2. Experiment with different content and style images, as well as adjusting parameters such as content weight and style weight, to achieve desired results.


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
