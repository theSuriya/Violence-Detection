# Violence Detection Model

This repository contains the code for a violence detection model using computer vision. The model uses the Inception V3 for feature extraction and an LSTM model for sequence classification, built with TensorFlow.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The violence detection model aims to identify violent activities in videos. This model leverages deep learning techniques for feature extraction and sequence modeling to detect violent behavior effectively.

## Features

- Feature extraction using Inception V3
- Sequence modeling using LSTM
- Built with TensorFlow
- End-to-end training and evaluation pipeline

## Installation

To use this project, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/violence-detection.git
    cd violence-detection
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To train the model, use the following command:

```bash
python train.py --dataset_path /path/to/dataset --epochs 50 --batch_size 32
