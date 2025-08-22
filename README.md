# 📘 Project README  

---

## 🔎 Project Overview  
This project explores the design and development of **machine learning and accessibility-focused applications** that address real-world problems in education, accessibility, healthcare, and safety.  

The main focus of our group was the **Braille Text-to-Audio Translator**, an innovative solution aimed at enhancing accessibility for individuals with visual impairments by automatically detecting and translating Braille characters into audio in real time.  

---

## 💡 Applications Proposed  

### 1️⃣ System of Recommendations for Education  
An application designed to recommend study paths for students based on their interests.  

---

### 2️⃣ Braille Text-to-Audio Translator *(Chosen Project)*  
- **Target**: Recognize and read Grade 1 Braille from images.  
- **Machine Learning Approach**: Supervised Learning – Multi-class Classification using **CNN with ReLU and Softmax**.  
- **Dataset**: [Kaggle – Braille Character Dataset](https://www.kaggle.com/datasets/shanks0465/braille-character-dataset?select=Dataset+Description.txt).  
- **Goal**: Extend to Grade 2 Braille (78 classes: 29 Grade 1 + 49 Grade 2).  
- **Similar Product**: [Braille Recognition iOS App](https://apps.apple.com/us/app/braille-recognition/id1669110413).  

---

### 3️⃣ Colour Distinguisher  
An application designed to help individuals with **colour vision deficiency** distinguish between different colours.  
- Reference: [Color Inspector App](https://appadvice.com/app/color-inspector/645516384).  

---

### 4️⃣ Prediction of Natural Disasters  
An application designed to **predict wildfires**, targeting suburban populations at risk.  

---

## 👥 Team Roles  
- **Coordinator**: Muhammad Fahad Sohail  
- **Facilitator**: Kwonmin Bok  
- **Notetaker**: Oyinkansola Ajibola  
- **Timekeeper**: Jianhui Qi  

---

## 🎯 Why Braille Text-to-Audio Translator?  
Braille remains vital for individuals with visual impairments, but traditional methods (touch-based reading or audio books) present challenges in real-world scenarios.  

Our solution leverages **smartphone cameras** and envisions future integration into **smart glasses**, enabling:  
- ✅ Real-time Braille detection and audio translation.  
- ✅ Hands-free accessibility without physical contact (post-COVID safety).  
- ✅ Usability in noisy or complex environments.  

---

## ⚙️ Practicality  
- **Target Audience**: English Grade 1 Braille users (with scalability to Grade 2).  
- **Feasibility**: Public datasets (Kaggle) and libraries (TensorFlow, Keras).  
- **Timeline**: Completion expected in a few months with iterative training and testing.  

---

## 🔍 Similar Products  
- Existing apps (e.g., *Braille Scanner*) require multiple steps for translation.  
- Our solution emphasizes **auto-detection** and **streamlined translation**, ensuring ease of use with minimal user interaction.  

---

## 🧠 Data & Model  
- **Input**: 28×28 pixel images of Braille characters.  
- **Output**: Corresponding English alphabet audio.  
- **Technique**: **Convolutional Neural Network (CNN)** with ReLU (hidden layers) and Softmax (output layer).  

**Justification**:  
1. CNN reduces dimensionality while retaining essential features.  
2. Multi-class classification handles multiple Braille characters effectively.  
3. Softmax ensures probabilistic accuracy in classification.  

---

## ⚠️ Limitations  
- Variability in captured Braille images (distortion, lighting, angles) may affect recognition accuracy.  

---

## 🔄 Alternatives Considered  
- **Linear Regression** → Not suitable for classification tasks.  
- **Perceptron** → Limited to binary outputs, unsuitable for multi-class Braille recognition.  
- **Decision Tree** → Too simplistic for handling complex Braille dot patterns.  

---

## 🚀 Key Takeaways  
- Applied **supervised learning** for accessibility innovation.  
- Explored **dataset preprocessing, CNN implementation, and real-world challenges**.  
- Focused on **usability, inclusivity, and scalability** for future assistive technologies.  

---

## 🛠️ Tech Stack  
- 🐍 Python  
- 🔷 TensorFlow  
- 📊 Keras  
- 📷 OpenCV  
- 🧮 NumPy & Pandas  

---

✨ **Resume Highlight**  
*“Developed a machine learning-based Braille Text-to-Audio Translator leveraging CNNs and Kaggle datasets to enhance accessibility for visually impaired individuals. Designed for real-time detection and translation, with scalability to Grade 2 Braille. Collaborated in a structured team environment, handling dataset preprocessing, model design, and evaluation.”*  
