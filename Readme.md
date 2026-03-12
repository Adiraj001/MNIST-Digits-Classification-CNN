# MNIST Digits Classification using CNN

## 👨‍💻 Author
**Aditya Raj Pandey**  
GitHub: https://github.com/Adiraj001

---

# 📌 Project Title
**Handwritten Digit Classification using Convolutional Neural Network (CNN)**

---

# 📖 Project Description
This project focuses on building a **Convolutional Neural Network (CNN)** model to classify handwritten digits from the **MNIST dataset**.  

The MNIST dataset contains **70,000 grayscale images of handwritten digits (0–9)**, each with a size of **28 × 28 pixels**. It is one of the most widely used benchmark datasets in machine learning and computer vision for image classification tasks. :contentReference[oaicite:0]{index=0}  

The objective of this project is to train a CNN model that can accurately recognize handwritten digits and classify them into their respective numeric labels.

---

# 📂 Dataset
The dataset used in this project is **MNIST**.

Dataset characteristics:

- 70,000 handwritten digit images
- 60,000 training images
- 10,000 testing images
- Image size: **28 × 28 pixels**
- Grayscale format
- Labels: digits **0 – 9**

---

# ⚙️ Methodology

The project follows these main steps:

### 1️⃣ Data Loading
- Load the MNIST dataset
- Split it into training and testing sets

### 2️⃣ Data Preprocessing
- Normalize pixel values (0–255 → 0–1)
- Reshape images to fit CNN input format

### 3️⃣ Model Architecture
A **Convolutional Neural Network (CNN)** is implemented with the following layers:

- Convolution Layer
- ReLU Activation
- Max Pooling Layer
- Flatten Layer
- Dense (Fully Connected) Layer
- Output Layer with Softmax

### 4️⃣ Model Training
- Loss Function: **Categorical Crossentropy**
- Optimizer: **Adam**
- Evaluation metric: **Accuracy**

### 5️⃣ Model Evaluation
- Evaluate the model using test data
- Measure classification accuracy

---

# 📊 Results

After training the CNN model:

- The model successfully classifies handwritten digits.
- High accuracy is achieved on the test dataset.
- The CNN model effectively learns patterns from the handwritten digit images.

Typical CNN models trained on MNIST achieve **~98–99% accuracy** depending on architecture and training parameters.

---

# 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Google Colab / Jupyter Notebook

---

# ▶️ How to Run the Project

### 1️⃣ Clone the repository

```bash
git clone https://github.com/Adiraj001/MNIST-Digits-Classification-CNN.git
```

# Install dependencies
```bash
pip install -r requirements.txt
```