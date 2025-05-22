# Resources

This file lists the key resources and references used to develop the Generative AI for Face Anonymization project, providing precise descriptions and direct links.

---

### 1. Face Alignment using dlib 68-Point Landmark Detection

- **Tutorial:** [dlib 68 Points Face Landmark Detection with OpenCV and Python](https://www.studytonight.com/post/dlib-68-points-face-landmark-detection-with-opencv-and-python)  
- **Description:** A comprehensive guide on detecting and aligning facial landmarks using dlib’s 68-point predictor. This technique ensures faces are normalized and aligned before further processing, improving downstream model accuracy.

---

### 2. Gender Classification Model (e.g., ResNet-18)

- **Example Repository:** [awaisjafar/Gender-Detection-Resnet-18](https://github.com/awaisjafar/Gender-Detection-Resnet-18)  
- **Description:** A PyTorch-based implementation of gender detection using ResNet-18 architecture with transfer learning. 

---

### 3. Project Motivation and Theoretical Background

- **Paper:** [“StyleGAN2: Analyzing and Improving the Image Quality of StyleGAN” (arXiv:2003.03581)](https://arxiv.org/abs/2003.03581)  
- **Description:** The foundational paper introducing StyleGAN2, detailing architectural improvements and motivations that enable high-fidelity, controllable face image generation. This work inspires the core image synthesis pipeline of the project.

---

### 4. Image Generation with StyleGAN2

- **Repository:** [NVIDIA/stylegan2](https://github.com/NVlabs/stylegan2)  
- **Description:** NVIDIA’s official implementation of StyleGAN2, a state-of-the-art generative adversarial network for producing realistic, high-resolution face images. This repository is used for latent space generation and gender-swapping transformations.

---

### 5. Image-to-Image Translation with Pix2PixHD

- **Repository:** [NVIDIA/pix2pixHD](https://github.com/NVIDIA/pix2pixHD)  
- **Description:** An advanced framework for high-resolution image-to-image translation tasks. Pix2PixHD refines StyleGAN2-generated images in pixel space to achieve seamless and visually convincing gender-swapped results.

---



### Summary

These resources collectively enable the pipeline from input face detection and alignment, through gender classification, to realistic and privacy-preserving gender-swapped face generation, forming the backbone of this generative AI project.
