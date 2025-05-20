 Classification and Detection of Cardiac Disorders using ECG Signals
📝 Overview
This project focuses on simplifying the early detection and classification of cardiac disorders using ECG signals. Cardiovascular diseases, such as arrhythmia, atrial fibrillation, and congestive heart failure, can be life-threatening if not diagnosed in time. We aim to leverage machine learning and deep learning techniques to accurately detect these abnormalities, thereby supporting medical professionals in timely diagnosis and treatment.

🎯 Objective
To build a robust system that classifies ECG signals into normal and abnormal patterns and detects specific cardiac disorders using machine learning (ML) and deep learning (DL) algorithms.

🧠 Techniques Used
Machine Learning Algorithms:

Support Vector Machine (SVM)

Random Forest

Naive Bayes

Deep Learning:

Convolutional Neural Network (CNN)

📊 Dataset
Source: Kaggle

Size: 1,200 ECG records with 54 features

Classes: Arrhythmia, Atrial Fibrillation, Congestive Heart Failure, Normal Sinus Rhythm

Preprocessing: Handled missing values, normalization, and applied Modulus Maxima Vehicular Packet Transform.

⚙️ Workflow
Data Collection

Preprocessing

Feature Visualization

Model Training (ML + DL)

Evaluation & Validation

Performance Comparison

📈 Results
Model	Accuracy
SVM	92.6%
Random Forest	97.6%
Naive Bayes	86.6%
CNN	99.58%

🔧 Libraries Used
NumPy

Pandas

Scikit-learn

TensorFlow / Keras

Matplotlib

📚 Future Scope
Integration with real-time ECG monitoring devices.

Deployment as a web/mobile application for real-time diagnosis.

Explore more ensemble learning methods for better generalization.

