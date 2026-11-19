# 🚦 Traffic Sign Classification Using Deep Learning

## 📌 Project Overview
This project uses Deep Learning and Convolutional Neural Networks (CNN) to classify traffic signs from images. The model is trained using the German Traffic Sign Recognition Benchmark (GTSRB) dataset to recognize different traffic sign categories.

## 🎯 Objectives
- Identify and classify different traffic signs.
- Build a CNN-based image classification model.
- Train and evaluate the model using image datasets.
- Explore AI applications in intelligent transportation systems.

## 🛠️ Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- OpenCV
- Jupyter Notebook

## 📂 Project Structure
```text
Traffic_Sign_Classification/
│
├── Train/                  # Training images
├── Test/                   # Testing images
├── Train.csv               # Training dataset labels
├── Test.csv                # Testing dataset labels
├── traffic_sign_model.keras
├── traffic_sign_model.h5
├── Traffic_Sign_Classification.ipynb
└── README.md
```

## ⚙️ Model Architecture
The project uses a Convolutional Neural Network (CNN) consisting of:
- Convolutional layers
- Max Pooling layers
- Flatten layer
- Dense layers
- Softmax output layer

## 📊 Model Performance
- **Test Accuracy:** 95.46%
- **Test Loss:** 0.1908

## 🚀 How to Run the Project

1. Clone this repository:
```bash
git clone https://github.com/your-username/Traffic_Sign_Classification.git
```

2. Install the required libraries:
```bash
pip install tensorflow numpy pandas matplotlib opencv-python
```

3. Open the Jupyter Notebook:
```bash
jupyter notebook
```

4. Run all cells to train and evaluate the model.

## 🌍 Applications
- Self-driving cars
- Intelligent transportation systems
- Road safety monitoring
- Driver assistance systems

## 👩‍💻 Author
**Aditi Padir**

AI & Data Science Student

## ⭐ Conclusion
This project demonstrates how deep learning can be used for traffic sign recognition and classification, contributing to safer and smarter transportation systems.
