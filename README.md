# 🖼️ Image Retrieval System using Deep Learning

This is a **mini-project** that implements a simple and effective **Image Retrieval System** using deep learning and pre-trained computer vision models.

Given a folder of images and a **query image**, the system retrieves the **top 5 most similar images** from the dataset using deep feature comparison.

---

## 🚀 Demo (Colab Notebook)

Run the project instantly in Google Colab with zero setup:

👉 [Click to Open in Colab](https://colab.research.google.com/drive/1ISUpWk8n_8_ZehCyCg42KTQFWdDjHptc?usp=sharing)

---

## 🧠 How It Works

- Uses **ResNet-50** pretrained on ImageNet to extract high-level features from images.
- Compares images using **FAISS** (Facebook AI Similarity Search) for fast nearest neighbor retrieval.
- Displays the query image alongside its **most visually similar matches**.

---

## 📂 Folder Structure

