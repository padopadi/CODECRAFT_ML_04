# 🤖 Hand Gesture Recognition - CODECRAFT_ML_04

This project implements a **Convolutional Neural Network (CNN)** to recognize hand gestures from grayscale images using the [LeapGestRecog dataset](https://www.kaggle.com/datasets/gti-upm/leapgestrecog).  
It enables gesture-based control systems and intuitive human-computer interaction.

---

## 📁 Dataset

- **Source**: [Kaggle - LeapGestRecog](https://www.kaggle.com/datasets/gti-upm/leapgestrecog)
- **Images**: 10 different gesture classes from 10 subjects
- **Grayscale, 64×64 resolution**

---

## 🧠 Model Architecture

- CNN with:
  - 2 × Conv2D + MaxPooling layers
  - 1 × Dense (128) + Dropout
  - Final output layer with Softmax (10 classes)

---

## 📊 Training & Results

- **Epochs**: 10  
- **Train/Val Split**: 80/20  
- **Final Test Accuracy**: `

<img width="209" height="51" alt="Screenshot 2025-07-21 193254" src="https://github.com/user-attachments/assets/e30c742f-6199-4cec-b65c-130a75d582f0" />


### 📈 Training Curve

> *(<img width="959" height="321" alt="Screenshot 2025-07-21 193213" src="https://github.com/user-attachments/assets/1973ce3f-e5ba-45fb-94b5-9192452b19ba" />
)*

---

## 💾 Files

- `hand_gesture_model.h5`: Saved Keras model  
- `CODECRAFT_ML_04.ipynb`: Colab notebook with full code  
- `README.md`: You’re reading it.

---

## 🔗 Links

- 👨‍💻 **Author**: [Yashika Sharma](https://www.linkedin.com/in/yashika-sharma-906932351)  
- 🐙 **GitHub**: [github.com/padopadi](https://github.com/padopadi)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
