📌 Project Overview

This project demonstrates image preprocessing and data augmentation techniques using TensorFlow and Keras. The main purpose is to enrich training datasets for deep learning models by applying transformations such as flipping, scaling, shifting, and brightness adjustment on sample images. These methods help prevent overfitting and improve the generalization ability of models like CNNs.

🛠️ Technologies & Libraries

Python

TensorFlow / Keras

NumPy

Matplotlib

SciPy

🔍 Features

Load and preprocess images (e.g., cat.jpg, kon.jpg)

Apply data augmentation techniques with ImageDataGenerator:

Horizontal & vertical flips

Brightness adjustments

Rescaling & zooming

Rotations & shifts

Visualize augmented images with Matplotlib

Generate larger and more diverse datasets for CNN training

📂 Project Structure

Untitled-44.ipynb → Jupyter Notebook containing the implementation

cat.jpg / kon.jpg → Example input images

README.md → Project documentation

🚀 How to Run

Clone the repository and navigate to the folder

Install required dependencies: pip install tensorflow matplotlib numpy scipy

Open the Jupyter Notebook: jupyter notebook Untitled-44.ipynb

Run the cells to see image preprocessing and augmentation results

📊 Example Results

Original images are transformed into multiple variations (flipped, rotated, scaled, etc.) that can be directly used in training deep learning models such as YOLO or CNN-based classifiers.
