
```markdown
# 🌱 Plant Disease Detection System for Sustainable Agriculture

## 📌 Overview
This project is a **Deep Learning-based Plant Disease Detection System** that identifies plant diseases from leaf images.  
It uses a **Convolutional Neural Network (CNN)** trained on a dataset of 39 plant disease categories and integrates with **Streamlit** to provide an easy-to-use web interface.

The goal is to help farmers and agricultural professionals **detect plant diseases early** for better crop management and sustainable agriculture.

---

## 🚀 Features
- **Image Upload & Processing** – Upload a plant leaf image and get instant predictions.
- **Deep Learning Model** – Trained on a labeled dataset of plant diseases.
- **39 Class Categories** – Detects a wide range of plant diseases and healthy states.
- **Google Search Integration** – Get more information about the detected disease with one click.
- **Interactive UI** – Built with Streamlit for smooth user interaction.

---

## 📂 Project Structure
```

├── PDD.ipynb        # Jupyter Notebook for model training and evaluation
├── front.py         # Streamlit application for user interface
├── CNN\_plantdiseases\_model.keras  # Trained model (not included here)
└── README.md        # Project documentation

````

---

## 🛠️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/plant-disease-detection.git
cd plant-disease-detection
````

### 2️⃣ Install dependencies

Make sure you have Python 3.8+ installed.

```bash
pip install -r requirements.txt
```

**requirements.txt** should include:

```
streamlit
tensorflow
numpy
opencv-python
```

### 3️⃣ Place the trained model

Download your trained CNN model (`CNN_plantdiseases_model.keras`) and place it in the project directory.
Update the path in `front.py` if necessary.

### 4️⃣ Run the Streamlit app

```bash
streamlit run front.py
```

---

## 💡 Usage

1. Launch the Streamlit app.
2. Select **DISEASE RECOGNITION** from the sidebar.
3. Upload a plant leaf image.
4. Click **Predict** to see the detected disease.
5. Click the generated Google link to learn more about it.

---

## 🖼️ Example Output

**Prediction:**

```
Model is predicting it's a Tomato___Leaf_Mold
```

**Google Link:**

```
https://www.google.com/search?q=Tomato+Leaf+Mold
```

---

## 📊 Model Information

* **Architecture:** Convolutional Neural Network (CNN)
* **Input Size:** 224x224 RGB images
* **Output:** Probability distribution over 39 classes
* **Dataset:** Standard plant disease dataset from Kaggle / PlantVillage

---


