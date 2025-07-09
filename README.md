# 🧠 Face Recognition with InsightFace + Flask

This project is a simple Flask-based web app that uses deep learning to recognize faces from photos.  
Currently, it's trained to recognize **Cristiano Ronaldo** and **Lionel Messi**, but you can easily add or replace photos with anyone else!

## 🚀 Features
- Upload any face photo and get a result: `Ronaldo`, `Messi`, or `Unknown`.
- Lightweight and fast — runs on CPU using InsightFace + FAISS.
- Responsive UI with Bootstrap.
- You can replace training photos with your own to recognize different people.

## 🖼️ How to Add Your Own Faces
Just put some clear images (JPG/PNG) of the person in the `known_faces/` folder, then run:

```bash
python enroll.py
