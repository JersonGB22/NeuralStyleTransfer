# <h1 align="center">**Neural Style Transfer**</h1>

This repository implements models for [neural style transfer](https://arxiv.org/abs/1508.06576), an optimization technique used to blend two images: a content image and a style reference image (e.g., artwork). The goal is to generate an output image that preserves the content of the former while adopting the visual style of the latter. This implementation optimizes the output image to match the content and style statistics of the input images, extracted through a convolutional neural network, using pre-trained models such as [VGG19 in Tensorflow](https://www.tensorflow.org/api_docs/python/tf/keras/applications/VGG19) and [VGG19 in PyTorch](https://pytorch.org/vision/main/models/generated/torchvision.models.vgg19.html). Additionally, it includes an implementation of Fast Neural Style Transfer in TensorFlow using a pre-trained model from [TensorFlow Hub](https://tfhub.dev/) for arbitrary image stylization.

## **Results**

- **The Persistence of Memory (Salvador Dalí) <-- The Starry Night (Vincent van Gogh)**

<p align="center">
<img src="images/neural_style_transfer/persistence_memory_starry_night/last_image.png"> 
</p>

- **Mona Lisa (Leonardo da Vinci) <-- Cubism (Juan Gris)**

<p align="center">
<img src="images/neural_style_transfer/mona_lisa_cubism/last_image.png"> 
</p>

- *Results across epochs*

<div style="display: flex; justify-content: center;">
    <div style="display: flex; justify-content: center; max-width: 800px;">
        <img src="images/neural_style_transfer/persistence_memory_starry_night/persistence_memory_starry_night.gif" style="width: 400px; margin-left: -100px;">
        <img src="images/neural_style_transfer/mona_lisa_cubism/mona_lisa_cubism.gif" style="width: 400px; margin-left: -100px;">
    </div>
</div>

- *Results with the TensorFlow Hub model*

<div style="display: flex; justify-content: center;">
    <div style="display: flex; justify-content: center; max-width: 800px;">
        <img src="images/fast_neural_style_transfer/persistence_memory_starry_night/gen_image.png" style="width: 400px; margin-left: -100px;">
        <img src="images/fast_neural_style_transfer/mona_lisa_cubism/gen_image.png" style="width: 400px; margin-left: -100px;">
    </div>
</div>

*You can find more examples in the model notebooks.*

## **Technological Stack**
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white&labelColor=101010)](https://docs.python.org/3/) 
[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white&labelColor=101010)](https://www.tensorflow.org/api_docs)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white&labelColor=101010)](https://pytorch.org/docs/stable/index.html)
[![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white&labelColor=101010)](https://plotly.com/)

## **Contact**
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white&labelColor=101010)](mailto:jerson.gimenesbeltran@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=101010)](https://www.linkedin.com/in/jerson-gimenes-beltran/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=101010)](https://github.com/JersonGB22/)