# Neural_Style_Transfer_GenAI

Welcome to the **Neural_Style_Transfer_GenAI** repository! This project uses TensorFlow and TensorFlow Hub to implement neural style transfer, a technique that merges the content of one image with the style of another.

## Project Overview

**Neural_Style_Transfer_GenAI** leverages a pretrained model from TensorFlow Hub, specifically Magenta's arbitrary-image-stylization-v1-256 model, to apply artistic styles to various content images. This method allows for the creation of unique, stylized images that maintain the original content's structure but mimic the artistic cues of the style reference.

## Features

- **Artistic Style Transfer**: Combines the content of one image with the style of another using deep neural networks.
- **Flexible Display Options**: Users can choose to display both the content and style images before and after the transfer.
- **Image Saving**: Offers the option to save the stylized images in different sizes and formats.

## Methodology

1. **Image Loading**: Images are loaded and preprocessed to ensure compatibility with the neural style transfer model. This includes resizing and normalizing the images.
2. **Style Transfer Application**: The style of one image is applied to the content of another using the model from TensorFlow Hub.
3. **Visualization**: The original, style, and stylized images can be displayed side by side for comparison.
4. **Saving and Output**: The final stylized image can be saved to disk, allowing for offline access and use.

This system is designed for artists, designers, and enthusiasts who wish to explore the creative possibilities of neural style transfer without deep knowledge of the underlying technology.
