# Image Denoiser with Autoencoders

This project implements a **convolutional autoencoder** to denoise handwritten digit images from the MNIST dataset. The model learns to reconstruct clean images from artificially noised inputs using deep learning.

---

## Features

- Loads and normalizes the MNIST dataset
- Adds Gaussian noise to training and test images
- Builds a convolutional autoencoder using TensorFlow/Keras
- Trains on noisy → clean image mappings
- Visualizes original, noisy, and denoised images
- Plots training and validation loss using Seaborn

---

## Model Architecture

```

Input: (28, 28, 1)
↓
Conv2D → ReLU → MaxPooling2D
↓
Conv2D → ReLU → MaxPooling2D
↓
Conv2D → ReLU → UpSampling2D
↓
Conv2D → ReLU → UpSampling2D
↓
Conv2D (Sigmoid) → Output: (28, 28, 1)

````

---

## Requirements

Install the required Python packages:

```bash
pip install -r requirements.txt
````

### Main Libraries:

* TensorFlow / Keras
* NumPy
* Matplotlib
* Seaborn

---

## Project Files

| File                          | Description                   |
| ----------------------------- | ----------------------------- |
| `denoising_autoencoder.ipynb` | Main Jupyter Notebook         |
| `requirements.txt`            | Python dependencies           |
| `images/`                     | Output image visualizations   |
| `.gitignore`                  | Common Python ignore patterns |

---


## Author

**Lourdhu Raju**
Available for AI/ML Developer roles

* [LinkedIn](https://linkedin.com/in/LourdhuRaju)
* [GitHub](https://github.com/Lourdhu02)

---

## Repository

[GitHub Repo → Image Denoiser with Autoencoders](https://github.com/Lourdhu02/image-denoiser-autoencoder)

