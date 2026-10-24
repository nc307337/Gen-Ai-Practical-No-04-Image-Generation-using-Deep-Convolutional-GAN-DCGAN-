# Gen-Ai-Practical-No-04-Image-Generation-using-Deep-Convolutional-GAN-DCGAN-


# Anime Face Generation Using GAN (DCGAN)

## 1. Project Overview
This project uses a Deep Convolutional Generative Adversarial Network (DCGAN) to generate anime-style face images.

A GAN consists of two neural networks:
- Generator: Generates fake anime faces from random noise.
- Discriminator: Distinguishes real anime images from generated images.

Both networks train together to improve the quality of generated images.

## 2. Dataset
Dataset Name: Anime Face Dataset

Kaggle Link:
https://www.kaggle.com/datasets/splcher/animefacedataset

Download the dataset and extract it into a folder on your computer.

Update the dataset path in the Python code:

```python
DATA_DIR = Path(r"D:\datasets\anime_data")
```

## 3. Technologies Used
- Python
- TensorFlow and Keras
- NumPy
- Matplotlib
- Pillow
- Jupyter Notebook

## 4. Installation
Run this command in a Jupyter Notebook cell:

```python
%pip install tensorflow numpy matplotlib pillow
```

## 5. How to Run the Project
1. Download the Anime Face Dataset from Kaggle.
2. Extract the dataset.
3. Open the GAN notebook in Jupyter Notebook.
4. Set the correct dataset folder path.
5. Run all notebook cells in order.
6. Train the GAN model.
7. View the generated anime face images.
8. Save the trained Generator and Discriminator models.

## 6. Model Configuration
- Image Size: 64 × 64 pixels
- Noise Vector Size: 100
- Batch Size: 64
- Number of Epochs: 50
- Optimizer: Adam
- Loss Function: Binary Cross-Entropy

These settings can be changed according to system performance.

## 7. Expected Output
Initially, generated images may look like random noise. During successful training, the Generator may learn anime facial features and produce more realistic images.

The quality of the output depends on dataset quality, training stability, and training duration.

## 8. Troubleshooting
- If no images are found, check the dataset path.
- If the ZIP file is invalid, download it again.
- If memory is insufficient, reduce the batch size.
- If output remains random noise, check the training loop, image normalization, and loss values.

## 9. Conclusion
This project demonstrates how GANs learn from real anime face images and attempt to generate new anime-style faces.

The project helps in understanding deep learning, image generation, and Generative Adversarial Networks.
