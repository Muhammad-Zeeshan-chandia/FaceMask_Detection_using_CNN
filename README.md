# 😷 Real-Time Face Mask Detection with Transfer Learning

This project uses a deep learning model trained with **transfer learning** on a custom dataset to detect whether a person is wearing a face mask in real-time via webcam. Built with TensorFlow/Keras and OpenCV.

---

## 📌 Highlights

- 🔍 Trained on a **custom face mask dataset**
- 🤖 Uses **transfer learning** ( VGG16)
- 🧊 Some layers **frozen** to retain pretrained features
- ✅ Binary classification: Masked vs No Mask
- 🎥 Real-time webcam detection

---

## 🧠 Model Details

- Base model: Pretrained on ImageNet ( `VGG16`)
- Layers frozen to retain learned features (e.g., `base_model.trainable = False`)

