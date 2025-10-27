# Hybrid Face Recognition System

## 📘 Project Overview
This project implements a **hybrid face recognition system** that integrates **deep learning** and **machine learning** methods for accurate single-face identification.  
It uses **Mediapipe** for face detection, **DenseNet121** and **Vision Transformer (ViT-B/16)** for feature embedding extraction, and **Cosine Similarity + Decision Tree** for classification.

## ⚙️ Features
- Detects and recognizes a single face in images or real-time webcam input  
- Extracts facial embeddings using **DenseNet121** and **ViT-B/16**
- Classifies identities using **Cosine Similarity** and **Decision Tree**
- Supports both image uploads and live webcam capture

## 🧠 Technologies Used
- **Python**, **PyTorch**, **OpenCV**, **Scikit-learn**, **Mediapipe**
- **Torchvision Models** – DenseNet121, Vision Transformer (ViT-B/16)

## 🚀 How It Works
1. Detects faces using Mediapipe  
2. Extracts deep embeddings via DenseNet121 and ViT-B/16  
3. Computes cosine similarity or applies Decision Tree classification  
4. Outputs the recognized person’s name or "Unknown"

## 📂 File Structure
```
face_recognition_onpoint.ipynb   # Main notebook
README.md                        # Project documentation
```
## 🧾 Output Example
```
✅ Detected: Harsha (Similarity: 0.89)
```
or
```
❌ Face not recognized — similarity below threshold
```

## 👨‍💻 Author
Developed by Harsha K  
B.Tech CSE (AI & ML) | Passionate about Data Science & Computer Vision

