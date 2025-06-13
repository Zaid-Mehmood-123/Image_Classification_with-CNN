<h1 align="center">
  🧠 CIFAR-10 Image Classification with CNN
</h1>

<p align="center">
  <img src="https://miro.medium.com/v2/resize:fit:800/format:webp/1*LRGrF1pS9nNhlgVgOY_M8Q.gif" width="280" alt="CNN Animation">
</p>

<p align="center">
  A deep learning project to classify images from the CIFAR-10 dataset into 10 distinct categories using a Convolutional Neural Network (CNN) built with TensorFlow and Keras.
</p>

---

## 📂 Dataset

The **CIFAR-10** dataset consists of 60,000 32x32 color images in 10 classes:
- ✈️ Airplane
- 🚗 Automobile
- 🐦 Bird
- 🐱 Cat
- 🦄 Deer
- 🐶 Dog
- 🐸 Frog
- 🧹 Horse
- 🚢 Ship
- 🚛 Truck

> 📦 50,000 training images and 10,000 testing images

---
<a id="contents_tabel"></a>    
<div style="border-radius:10px; padding: 15px; background-color: #e2c9ff; font-size:125%; text-align:left">

<h2 align="left"><font color=#8502d1>Table of Contents</font></h2>
    
* [Step 1 | Import Necessary Libraries](#import)
* [Step 2 | Data Preparation and Exploration](#exploration)
* [Step 3 | Data Preprocessing](#preprocessing)
    - [Step 3.1 | Normalization of Image Data](#normalization)
    - [Step 3.2 | One-Hot Encoding of Labels](#onehot)
    - [Step 3.3 | Data Augmentation](#augmentation)
* [Step 4 | Define CNN Model Architecture](#cnn)
* [Step 5 | Training the CNN Model](#train)
* [Step 6 | Visualizing the Learning Curves](#curves)
* [Step 7 | Evaluating the Optimal Model on Test Data](#evaluation)
* [Step 8 | Performance on an Out-of-Dataset Image](#image)
  
---
## 🚀 Features

- ✅ Convolutional Neural Network (CNN) architecture
- ✅ Data preprocessing and normalization
- ✅ Data Augmentation for improved generalization
- ✅ Training and evaluation on CIFAR-10
- ✅ Visualization of accuracy and loss curves
- ✅ Model performance summary with classification report

---

## 📊 Model Performance

| Metric      | Value   |
|-------------|---------|
| Training Accuracy | ~85% |
| Test Accuracy     | ~80% |
| Loss              | Decreases steadily with epochs |

> 📈 Performance may vary depending on architecture tuning and augmentation

---

## 🧪 How to Run

```bash
# Step 1: Clone the repository
git clone https://github.com/yourusername/cifar10-cnn.git
cd cifar10-cnn

# Step 2: Install required packages
pip install tensorflow numpy matplotlib seaborn

# Step 3: Run the notebook
jupyter notebook CIFAR10_CNN.ipynb
```
📷 Sample Output

<p align="center"> <img src="https://raw.githubusercontent.com/yourusername/cifar10-cnn/main/assets/output_sample.png" width="600"> </p>
---
🧠 Model Architecture

Conv2D -> MaxPooling -> Conv2D -> MaxPooling -> Flatten -> Dense -> Dropout -> Output

Optimizer: Adam

Loss: Categorical Crossentropy

Activation: ReLU and Softmax
---
👤 Author

Zaid Mehmood

🎓 AI Student @ Superior University

📍 Lahore, Pakistan

📧 zaidmehmood0123@gmail.com

🌐 LinkedIn "ZAID MEHMOOD"

---
🌟 Show Some Love

If you found this project helpful or interesting, give it a ⭐ and share it with your friends and community!

---
🏷️ Tags

#deep-learning #cnn #tensorflow #keras #image-classification #cifar10 #computer-vision
