# Generative AI for Face Anonymization

## Overview
This project addresses privacy concerns in AI-generated imagery by **anonymizing human faces** without sacrificing data utility. Using **StyleGAN2** and **Pix2PixHD**, it performs **gender swapping** in both latent and pixel space to generate realistic, high-resolution anonymized images while preserving key attributes (e.g., hair, background, pose).

## Key Features
- **StyleGAN2 + Pix2PixHD Integration**: Produces authentic facial images with seamless high-resolution transformations.
- **Gender-Swap Anonymization**: Obscures identity by altering gender-specific traits, retaining nonidentity features.
- **Cosine Similarity Scoring**: Measures similarity between the original and anonymized image to balance privacy and fidelity.
- **Easy Colab Deployment**: Jupyter Notebook-based setup with free GPU access—no manual environment configuration required.

## Project Motivation
As AI gains traction in image generation, **privacy compliance** has become a critical challenge. This project aims to **protect individual identities** while still allowing researchers to leverage large, diverse datasets for model development.

## Repository Contents
- **Model/Code**: Core scripts for preprocessing, classification (ResNet18), and the StyleGAN2/Pix2PixHD pipelines.
- **notebooks/**: Google Colab-ready Jupyter Notebooks for face upload, anonymization, and result analysis.
- **results/**: Sample outputs, logs, or performance metrics.
- **docs/** (optional): Additional documentation or user guides.

## How It Works
1. **Upload an Image**: Provide a supported image (JPG, PNG, etc.).
2. **Face Alignment**: Detects and aligns the face automatically.
3. **Gender Classification**: Uses a ResNet18-based model to classify the image as male or female.
4. **Gender Swap**: StyleGAN2 and Pix2PixHD generate a high-resolution, anonymized image of the opposite gender.
5. **Cosine Similarity**: Calculates a similarity score, ensuring privacy with preserved key features.

## Getting Started
1. **Launch in Colab**: [Click here](https://colab.research.google.com/drive/15RFBtXzo-lvKwMCkgh_0ZgeCASOPOgLE?usp=sharing) to open the notebook.
2. **Run All Cells**: Follow the prompts to upload your image, run anonymization, and view/save results.
3. **Adjust Parameters**: Customize thresholds or model settings within the notebook for different anonymization levels.

## Prerequisites
- **Google Colab** (recommended)  
- **Python 3.x** (if running locally)  
- **Deep Learning Framework** (TensorFlow or PyTorch, depending on your implementation)  
- **Libraries**: NumPy, scikit-learn, Pillow, Matplotlib, dlib, etc.  
*(All required libraries are typically pre-installed in Colab.)*

---

**Questions or Contributions?**  
- Please open an issue or pull request.  
