# Medical Image Captioning – Report Generation

## Overview
This project implements an automated captioning system for chest X-ray images by combining a CNN-based visual encoder with a transformer-based text decoder. 
The pipeline extracts meaningful radiological features using DenseNet121 and generates structured, clinically-aware descriptions to support diagnostic workflows.

## Features

* High-quality feature extraction using a fine-tuned DenseNet121 encoder

* Transformer decoder for generating context-aware clinical captions

* End-to-end workflow including preprocessing, training, inference, and evaluation

* Radiology-focused vocabulary for more accurate and meaningful reports

* Modular architecture that can be extended to other imaging modalities

## How It Works

1. Preprocessing: Images are normalized, resized, and cleaned.

2. Encoding: DenseNet121 extracts high-level visual features from X-rays.

3. Decoding: A transformer-based decoder generates captions based on the encoded features.

4. Training: Cross-entropy loss with teacher forcing for stable convergence.
