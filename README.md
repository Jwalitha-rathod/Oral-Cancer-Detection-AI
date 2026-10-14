# 🩺 Oral Cancer Detection Using Deep Learning

## 📌 Project Overview

This project focuses on detecting oral cancer from images using deep learning and computer vision techniques. It explores convolutional neural network architectures to classify images into two categories: **Cancer** and **Normal**.

The project uses TensorFlow and Keras for model development and explores TensorFlow Lite for deployment on resource-constrained edge devices such as the Raspberry Pi.

## 🎯 Objectives

- Develop an image-based oral cancer classification system.
- Train and evaluate deep learning models for cancer detection.
- Compare MobileNetV2 and EfficientNetB0 architectures.
- Explore lightweight model deployment using TensorFlow Lite.
- Investigate the use of edge computing for AI-based medical image analysis.

## 🧠 Models Used

- **MobileNetV2:** A lightweight convolutional neural network suitable for efficient image classification.
- **EfficientNetB0:** An efficient deep learning architecture for image classification.

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Matplotlib
- MobileNetV2
- EfficientNetB0
- TensorFlow Lite
- Google Colab
- Raspberry Pi

## 📊 Results

The project achieved the following reported accuracy values during experimentation:

| Environment | Reported Accuracy |
|---|---:|
| Google Colab | 94.10% |
| Raspberry Pi | 87% |

These values reflect the results obtained in the respective experimental environments. Performance may vary depending on the dataset, preprocessing, model configuration, and evaluation procedure.

## ⚙️ Project Workflow

1. Load and prepare the oral cancer image dataset.
2. Organize images into training, validation, and testing sets.
3. Preprocess images for model training.
4. Train and evaluate deep learning models.
5. Compare classification performance.
6. Explore deployment using TensorFlow Lite on Raspberry Pi.

## 💻 Run the Project

### Option 1: Google Colab

1. Open the Jupyter notebook in this repository.
2. Open it in Google Colab.
3. Configure the dataset paths and provide access to the required dataset.
4. Run the notebook cells in order.

### Option 2: Local Environment

Install the main dependencies:

```bash
pip install tensorflow opencv-python numpy matplotlib
```

Open the notebook using Jupyter Notebook or JupyterLab. Update the dataset paths to match your local environment before running the code.

**Note:** The dataset is not included in this repository. You must obtain the dataset separately and configure the paths used in the notebook.

## 📂 Repository Contents

- `Oral_Cancer_Detection.ipynb` – Jupyter notebook containing the project implementation.
- `README.md` – Project documentation.

## 🔮 Future Improvements

- Evaluate performance on additional and independent datasets.
- Improve model generalization and robustness.
- Include detailed classification metrics such as precision, recall, F1-score, and confusion matrices.
- Optimize the model for edge-device deployment.
- Develop a user-friendly interface for image-based predictions.

## ⚠️ Disclaimer

This project is intended for educational and research purposes only. It is not a clinically validated diagnostic system and must not be used as a substitute for professional medical evaluation.

## 👩‍💻 Author

**Banothu Jwalitha Rathod**

B.Tech, Electronics and Communication Engineering  
National Institute of Technology Puducherry

## 🔗 Project Notebook

[View the source code on GitHub](https://github.com/Jwalitha-rathod/Oral-Cancer-Detection-AI/blob/main/Oral_Cancer_Detection.ipynb)
