🧠 #Early Detection & Classification of Alzheimer’s Disease (MRI-Based)

A Multi-Model Deep Learning & Explainable AI Approach

🔍 Overview

#Alzheimer’s Disease (AD) is a progressive neurodegenerative disorder, and early detection is critical for timely intervention.
This research explores multiple machine learning and deep learning models on MRI scans to classify:

🟢 Non-Demented

🟡 Very Mild Demented

🟠 Mild Demented

🔴 Moderate Demented

Our work integrates explainable AI (Grad-CAM) to understand model decisions, highlighting critical brain regions influencing predictions.

🚀 Model Approaches Used

We performed a comprehensive comparison across classical ML + deep learning models:

🟣 1. K-Nearest Neighbors (KNN)

Baseline classical ML classifier

Useful for feature-based comparison

🟡 2. Ensemble Model

Combines multiple weak learners

Boosts overall stability & generalization

🔵 3. CNN with Fine-Tuning (Best Model)

Transfer Learning + custom layers

Achieved 95% Accuracy 🎯

🟠 4. Combined Dual-CNN Architecture

Parallel feature extraction

Improved depth of learned representations

🔎 Explainable AI with Grad-CAM

To ensure reliability & interpretability:

🔥 Class activation maps highlight regions influencing the model’s decision

🧠 Helps verify whether CNN focuses on medically relevant brain structures

📊 Supports trust-building in clinical settings

✨ Key Highlights

✔ 95% accuracy with Fine-Tuned CNN (best-performing model)
✔ Comparative analysis of ML & DL architectures
✔ Complete pipeline for:

Preprocessing

Data augmentation

Model training

Evaluation metrics

Visualization
✔ Grad-CAM integration for interpretability
✔ Clean, modular, and reproducible research workflow

📂 Included in This Repository

📁 Dataset preprocessing scripts

🧪 Training notebooks

📉 Accuracy, loss & confusion matrix plots

🔥 Grad-CAM visualization outputs

🧩 Model comparison report

🧠 Complete reproducible deep learning pipeline

📘 Perfect For

Medical imaging research

Explainable AI projects

Deep learning classification tasks

Students & researchers exploring Alzheimer’s detection
