Project Overview

This project explores the design and development of machine learning and accessibility-focused applications that address real-world problems in education, accessibility, healthcare, and safety. The applications are proposed, discussed, and evaluated within a collaborative team setting.

The main focus of our group was the Braille Text-to-Audio Translator, an innovative solution aimed at enhancing accessibility for individuals with visual impairments by automatically detecting and translating Braille characters into audio in real time.

Applications Proposed

System of Recommendations for Education

Application designed to recommend study paths for students based on their interests.

Braille Text-to-Audio Translator (Chosen Project)

Target: Recognize and read Grade 1 Braille from images.

Machine Learning Approach: Supervised Learning – Multi-class Classification using CNN with ReLU and Softmax.

Dataset: Kaggle – Braille Character Dataset
.

Goal: Extend to Grade 2 Braille (78 classes: 29 Grade 1 + 49 Grade 2).

Similar Products: Braille Recognition iOS App
.

Colour Distinguisher

Application designed to help individuals with colour vision deficiency distinguish between different colours.

Reference: Color Inspector App
.

Prediction of Natural Disasters

Application focused on predicting wildfires, targeting suburban populations at risk.

Team Roles

Coordinator: Muhammad Fahad Sohail

Facilitator: Kwonmin Bok

Notetaker: Oyinkansola Ajibola

Timekeeper: Jianhui Qi

Why Braille Text-to-Audio Translator?

Braille remains vital for individuals with visual impairments, but traditional methods (touch-based reading or audio books) present challenges in real-world scenarios. Our solution leverages smartphone cameras and envisions future integration into smart glasses, enabling:

Real-time Braille detection and audio translation.

Hands-free accessibility without physical contact (post-COVID safety).

Usability in noisy or complex environments.

Practicality

Target Audience: English Grade 1 Braille users, with scalability to Grade 2 Braille.

Feasibility: Public datasets (Kaggle), pre-developed libraries (TensorFlow, Keras).

Timeline: Expected completion in a few months with iterative training and testing.

Similar Products

Existing apps (e.g., Braille Scanner) require multiple steps for translation, making them inconvenient.

Our solution emphasizes auto-detection and streamlined translation, ensuring ease of use with minimal user interaction.

Data & Model

Input: 28×28 pixel images of Braille characters.

Output: Corresponding English alphabet audio.

Technique: Convolutional Neural Network (CNN) with ReLU (hidden layers) and Softmax (output layer).

Justification:

CNN reduces dimensionality while retaining image features.

Multi-class classification handles multiple Braille characters effectively.

Softmax ensures probabilistic accuracy in classification.

Limitations

Variability in captured Braille images (distortion, lighting, angles) may affect recognition accuracy.

Alternatives Considered (and why not chosen)

Linear Regression: Not suitable for classification tasks.

Perceptron: Limited to binary outputs, unsuitable for multi-class Braille recognition.

Decision Tree: Too simplistic to handle complex Braille dot patterns.

Key Takeaways

Applied supervised learning techniques for accessibility-focused innovation.

Explored dataset preprocessing, CNN implementation, and real-world challenges.

Emphasized usability, inclusivity, and scalability to future assistive technologies.
