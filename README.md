# 🧠 Image Classification with CNN (CIFAR-10)

This project demonstrates a Convolutional Neural Network (CNN) built using TensorFlow and Keras to classify images from the CIFAR-10 dataset.

---

## 📚 Dataset
- **CIFAR-10**: 60,000 32x32 color images in 10 classes:
  `airplane`, `automobile`, `bird`, `cat`, `deer`, `dog`, `frog`, `horse`, `ship`, and `truck`

---

## 🧠 Model Architecture
```
Conv2D (32 filters, 3x3, ReLU)  
MaxPooling2D (2x2)  
Conv2D (32 filters, 3x3, ReLU)  
MaxPooling2D (2x2)  
Flatten  
Dense (64 units, ReLU)  
Dense (10 units, Softmax)
```

---

## 📊 Results
- Trained on 50,000 training images
- Evaluated on 10,000 test images
- Loss Function: Sparse Categorical Crossentropy
- Optimizer: Adam

> Final Accuracy: ~ (fill in after training)

---

## 🚀 How to Run
1. Clone the repo  
2. Install dependencies:  
```bash
pip install -r requirements.txt
```
3. Run the Jupyter Notebook:
```bash
jupyter notebook Image_Classification_Annotated_Final.ipynb
```

---



---

## 🙌 Acknowledgements
- TensorFlow & Keras
- CIFAR-10 dataset from [https://www.cs.toronto.edu/~kriz/cifar.html](https://www.cs.toronto.edu/~kriz/cifar.html)

---

⭐ Star the repo if you like it!

