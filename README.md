# GAN-Based Video Super-Resolution

## 📌 Overview
This project applies a GAN-based approach to super-resolve low-resolution CCTV and webcam videos, targeting real-time enhancement in video conferencing and surveillance systems.

## 🧠 Problem Solved
Low-resolution and blurred videos hinder detail visibility in real-time applications. This project improves visual clarity using a GAN model, handling motion blur, compression artifacts, and lighting issues.

## 🛠️ Tech Stack
- PyTorch
- OpenCV
- GAN Architecture (Custom Generator and Discriminator)
- Jupyter Notebook

## 🚀 Features
- GAN model training for super-resolution
- Trained Generator and Discriminator weights included
- Output demo video comparison provided
- Notebook includes PSNR/SSIM evaluation and visualization

## 📁 Files
- `debluremodel.ipynb` - Code to train and evaluate the model
- `gan_generator.pth` - Pre-trained generator model
- `gan_discriminator.pth` - Pre-trained discriminator model
- `comparison_video.mp4` - Output vs Input video
