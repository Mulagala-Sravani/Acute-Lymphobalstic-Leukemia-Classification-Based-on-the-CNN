# Acute Lymphoblastic Leukemia Classification Based on Convolutional Neural Networks

This project implements a **Convolutional Neural Network (CNN)** model for classifying blood smear images to assist in the early diagnosis of **Acute Lymphoblastic Leukemia (ALL)**.

The goal of this project is to provide an AI-powered tool that can help pathologists quickly and accurately classify cell images into ALL subtypes or benign categories.

---

## 🌐 Project Link

👉 Local development server: [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

---

## 🚀 Technologies Used

- **Python 3.x**
- **Django** (Backend Framework)
- **TensorFlow / Keras** (CNN Model)
- **OpenCV** (Image Preprocessing)
- **SQLite3** (Database)
- **HTML / CSS** (Frontend)

---

## ⚙️ Features

- ✅ Upload blood smear images via web interface
- ✅ Preprocess images (resize, normalize, augment)
- ✅ Classify images using trained CNN model
- ✅ Display prediction results on the UI
- ✅ Local hosting on Django server
- ✅ Easily extensible for production deployment (Heroku, AWS, GCP, etc.)

---

## 🗂️ How to Run Locally

### 1️⃣ Clone this repository:

```bash
git clone https://github.com/Mulagala-Sravani/Acute-Lymphoblastic-Leukemia-Classification-Based-on-the-CNN.git
cd Acute-Lymphoblastic-Leukemia-Classification-Based-on-the-CNN

### 2️⃣ Create a virtual environment & activate

```bash
python -m venv venv
venv\Scripts\activate   # For Windows
# OR
source venv/bin/activate   # For Linux/Mac

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt

### 4️⃣ Run Django migrations

```bash
python manage.py migrate

### 5️⃣ Start the server

```bash
python manage.py runserver

### 6️⃣ Access the application

👉 Open your browser and visit:  
[http://127.0.0.1:8000/](http://127.0.0.1:8000/)



