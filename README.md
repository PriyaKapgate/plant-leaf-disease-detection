# 🌿 Plant Disease Detection using Deep Learning

## 📌 Project Overview

Plant Disease Detection is a Deep Learning project that identifies diseases in plant leaves using images.

The project uses a **Convolutional Neural Network (CNN)** built with **PyTorch** to classify leaf images into **39 different categories**.

The model is trained on the **PlantVillage dataset**.

---

## 🚀 Technologies Used

* Python 3.8
* PyTorch
* CNN (Convolutional Neural Network)
* Flask (Web App)
* HTML, CSS (Frontend)

---

## 📂 Dataset

* **PlantVillage Dataset**
* Contains images of healthy and diseased plant leaves.

---

## ⚙️ How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone <your-repository-link>
cd Plant-Disease-Detection
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
```

Activate Environment:

**Windows**

```bash
venv\Scripts\activate
```

**Mac/Linux**

```bash
source venv/bin/activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Download Pre-trained Model

Download the model file:
**plant_disease_model_1.pt**
Place it inside the **Flask Deployed App** folder.

[Download Link](https://drive.google.com/drive/folders/1ewJWAiduGuld_9oGSrTuLumg9y62qS6A?usp=share_link)

### 5️⃣ Run the Application

```bash
python app.py
```

Open browser and go to:

```
http://127.0.0.1:5000/
```

---

## 🧪 Testing

* Use sample images from the `test_images` folder.
* Upload a leaf image and the model will predict the disease.

---

## 🌐 Features

* Upload plant leaf image
* Predict plant disease
* Display result on web page
* Simple and user-friendly UI

---

## 📌 Future Improvements

* Increase model accuracy
* Add more plant categories
* Deploy on cloud (AWS/Heroku)
* Mobile app integration

---

## 👩‍💻 Author

**Priya Kapgate**

---

