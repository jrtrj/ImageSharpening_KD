# Intel&reg;
# Problem Statement 2:
# Image Sharpening Using Knowledge Distillation 

In this project we are using the CNN architecture based model to develop a student model that restores the quality of a bad frame due to the senders poor bandwidth while maintaining the same quality to the recepeint on their side 

To clone the repo use the code below:
```
  git clone https://github.com/jrtrj/ImageSharpening_KD.git
```
# Description 
This project aims to enhance image sharpness in real-time video conferencing by
designing a lightweight deep learning model. We adopt a knowledge distillation
approach, where a high-performing ResNet-based teacher model guides a student model optimized for real-time performance. Evaluation is performed using SSIM and MOS.

# Limitations
- Limitations in computational power to run and use heavy pretrained models.

# Outcomes 
- Gained knowledge about CNN
- Able to fine tune models

# Future Scope 
- Integrating the student model into video conferencing pipelines to enhance live video quality.
- Train the model more on real video conferencing image datasets
  
# Libraries Used
- **`os:`** Provides a way of using operating system dependent functionality like reading or writing to the file system.
- **`cv2:`** A comprehensive library for computer vision tasks, including image loading, processing, and manipulation.
- **`glob:`** Finds all the pathnames matching a specified pattern, useful for listing files in directories.
- **`numpy:`** The fundamental package for numerical computation in Python, providing powerful array objects and mathematical functions.
- **`torch:`** The core PyTorch library, enabling tensor computation and deep learning model building.
- **`torch.nn:`** Contains modules and classes for building neural networks in PyTorch, such as layers and activation functions.
- **`torch.optim:`** Provides various optimization algorithms (e.g., SGD, Adam) used to train neural networks.
- **`torch.utils.data:`** Offers utilities for data loading, including Dataset and DataLoader for efficient batch processing.
- **`torchvision.transforms:`** Includes common image transformations for data augmentation and preprocessing in computer vision.
- **`torchvision.models:`** Provides pre-trained models for various computer vision tasks, which can be used for transfer learning.
- **`pytorch_msssim:`** Implements the Multi-scale Structural Similarity Index Measure (MS-SSIM) as a PyTorch loss function.
- **`albumentations:`** A fast and flexible library for image augmentations, offering a wide range of transformations.
- **`skimage.metrics:`** Provides functions for image quality assessment, including the standard SSIM metric.
- **`torch.optim.lr_scheduler:`** Offers methods for adjusting the learning rate during training, such as Cosine Annealing.
- **`matplotlib.pyplot:`** A plotting library used for creating static, interactive, and animated visualizations in Python.
  
# Dataset Used
  <a href="https://data.vision.ee.ethz.ch/cvl/DIV2K/" target="_blank">DIV2K</a>
# Team Members
- <a href="https://github.com/jrtrj" target="_blank">Jerit Reji</a>
- <a href="https://github.com/sebastian-abraham" target="_blank">Sebastian Abraham</a>
- <a href="https://github.com/JoThePOkeMOn" target="_blank">Joel Mathew Samuel</a>

