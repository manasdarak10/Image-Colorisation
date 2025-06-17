# 🖼️ Image Colorisation using GANs

This project implements a **Generative Adversarial Network (GAN)** for automatic **image colorisation** of grayscale photos. It learns to colorize black-and-white images by training on paired datasets using a neural network architecture.

## 🧠 Features
- Uses a custom image dataset for training
- Converts grayscale images to RGB
- Utilizes GAN architecture with generator and discriminator models
- Trains and visualizes progress with sample outputs
- Implemented in Jupyter Notebook using TensorFlow/Keras

## 📁 Project Structure
```
Image-Colorisation/
├── gan_image_colorisation.ipynb   # Main notebook with model and training loop
├── dataset/                       # Folder containing training images
├── requirements.txt               # Python dependencies
└── README.md                      # Project documentation
```

## 🧾 Dataset
- The dataset file includes a link to kaggle, which contains the landscape images, both grapscale and color images (7129 each)

## ⚙️ How It Works
1. The generator learns to colorize grayscale images.
2. The discriminator distinguishes real vs generated color images.
3. Both networks are trained together in a GAN loop.
4. Results are visualized as training progresses.

## 🧰 Technologies Used
- Python 3.8+
- TensorFlow / Keras
- NumPy
- OpenCV
- Matplotlib

## 🚀 Getting Started

### Step 1: Clone the repository
```bash
git clone https://github.com/manasdarak10/Image-Colorisation.git
cd Image-Colorisation
```

### Step 2: Install dependencies
```bash
pip install -r requirements.txt
```

### Step 3: Run the notebook
```bash
jupyter notebook gan_image_colorisation.ipynb
```

### Step 4: Add images
- Place your training images inside the `dataset/` directory.
- Modify paths in the notebook if necessary.
