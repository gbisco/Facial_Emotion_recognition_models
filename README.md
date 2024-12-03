# Facial Emotion Recognition Models

This project demonstrates the application of deep learning techniques for **facial emotion recognition** using **transfer learning** and custom CNNs. By leveraging pre-trained convolutional neural networks (CNNs) such as **VGG16**, **ResNet50**, and **EfficientNet**, the model are fine-tuned to classify emotions from facial images into predefined categories.

---

## Features
- **Preprocessing:** Image resizing, augmentation, and normalization for optimal model training.
- **Transfer Learning:** Utilization of pre-trained CNN architectures with custom classification layers.
- **Experimentation:**
  - Comparing model architectures like VGG16, ResNet50, EfficientNet, and custom made.
  - Fine-tuning selective layers to improve performance.
  - Employing activation functions like **LeakyReLU** and layers such as **GlobalAveragePooling2D** for better accuracy.
- **Visualization:** Graphs for training and validation metrics, and sample image displays from the dataset.
- **Regularization:** Dropout and L2 regularization to reduce overfitting.

---

## Installation and Setup

### Prerequisites
- Python 3.7+
- TensorFlow 2.x
- Required libraries listed in `requirements.txt`.

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/emotion-recognition.git
   cd emotion-recognition

2. Install dependencies:
   pip install -r requirements.txt
   
3. Ensure the dataset is in the appropriate directory structure:
     /Data
  /train
    /happy
    /sad
    /angry
    /neutral
  /validation
    /happy
    /sad
    /angry
    /neutral

### Contributing
Pull requests are welcome. For significant changes, please open an issue first to discuss your ideas.
