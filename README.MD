# EyeGuardian Model

## Overview

The **EyeGuardian Model** is an AI-based solution designed to classify ocular diseases from retinal images. This project uses FastAI and the ResNet18 architecture to achieve high accuracy in detecting conditions such as Diabetic Retinopathy, Cataracts, Glaucoma, and Hypertension. The model aims to assist in the early diagnosis and management of these eye diseases.

## Features

- **Image Classification:** Accurately classifies retinal images into various ocular disease categories.
- **High Accuracy:** Utilizes ResNet18 for effective and reliable predictions.
- **User-Friendly:** Simple interface for image input and results output.

## Project Structure

- **Image Search and Download:** Fetches retinal images from online sources and downloads them for dataset creation.
- **Image Preprocessing:** Resizes and verifies image integrity to prepare data for model training.
- **Data Preparation:** Organizes images into training and validation sets for model training.
- **Model Training:** Uses FastAI to train a ResNet18 model on the prepared dataset.
- **Prediction:** Classifies new retinal images and provides disease predictions with probability scores.

## Installation

To run this project, you need Python and the following libraries:

```bash
pip install fastai duckduckgo_search fastdownload
