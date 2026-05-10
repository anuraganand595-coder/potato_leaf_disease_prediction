# 🌿 Potato Leaf Disease Prediction System

A deep learning-based web application that detects and classifies potato leaf diseases using transfer learning with EfficientNetB7. The system helps identify common potato plant diseases from uploaded leaf images and provides real-time predictions through a Flask web interface.

---

## ✨ Features

- Upload potato leaf images for disease prediction
- Detects:
  - Early Blight
  - Late Blight
  - Healthy Leaves
- Deep learning model using EfficientNetB7
- Transfer Learning based image classification
- Flask-based user-friendly web interface
- Real-time prediction results

---

## 🛠️ Tech Stack

- Python
- Flask
- TensorFlow / Keras
- EfficientNetB7
- HTML/CSS
- NumPy

---

## 🧠 Model Details

- Base Model: EfficientNetB7
- Transfer Learning Approach
- Image Size: 224 × 224
- Activation Function: Softmax
- Optimizer: Adam
- Framework: TensorFlow/Keras

---

## 📁 Project Structure

```text
Potato_Leaf_Project/
│
├── app.py
├── requirements.txt
├── .gitignore
├── README.md
│
├── templates/
│   └── index.html
│
├── static/
│   └── uploads/
```

---

## 📚 Dataset

The model was trained using the PlantVillage dataset containing potato leaf images categorized into:

- Potato Early Blight
- Potato Late Blight
- Healthy Potato Leaves

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/anuraganand595-coder/potato_leaf_disease_prediction.git
```

Move to project directory:

```bash
cd potato_leaf_disease_prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Download Trained Model

The trained model file is not uploaded to GitHub due to GitHub file size limitations.

Download the model file from:

```text
https://drive.google.com/file/d/1XqfOGUeNBcjuEFIKKQzMPjGdy3rPvgmv/view?usp=drivesdk
```

After downloading, place:

```text
eff.weights.h5
```

inside the project root directory.

---

## ▶️ Run the Application

```bash
python app.py
```

Open browser:

```text
http://127.0.0.1:5000
```

---

## 🔮 Future Improvements

- Add support for more plant diseases
- Deploy using Docker/Cloud platforms
- Mobile-friendly UI
- Real-time camera detection
- Improve model accuracy using data augmentation

---

## 👨‍💻 Author

### Anurag Anand

GitHub: https://github.com/anuraganand595-coder
