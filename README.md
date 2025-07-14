# 🧓HumanActionRecognition_Using-Modern-Deep-learning-techniques
    A final year MSc in Data Analytics project submitted to Dublin Business School
    Developed by Venkaiah Malli
## 📌 Project Overview

This project compares the performance of four deep learning models—Vanilla CNN, ResNet50, MobileNetV2, and Vision Transformer (ViT)—on a Human Action Recognition (HAR) task using RGB images. The objective was to classify 15 different human actions from over 12,000 images and determine the most effective architecture.

## 🧠 Core Features

- Implementation of four deep learning models with consistent parameters
- Use of Kaggle HAR dataset with preprocessing, augmentation, and label encoding
- Application of CRISP-DM methodology throughout the project
- Model evaluation using accuracy, F1-score, AUC-ROC, and confusion matrices
## 📁 Repository Structure

```
📦Human_Action_Recognition_DL
 ┣ 📂Notebooks
 ┃ ┗ 📜HAR_All_Models.ipynb
 ┣ 📂Visuals
 ┃ ┗ 📜Confusion matrix & ROC curves
 ┣ 📂Docs
 ┃ ┣ 📜HAR_Report.pdf
 ┃ ┗ 📜HAR_Presentation.pdf
 ┣ 📜README.md
 ┣ 📜requirements.txt
```
## 🧪 Results

| Model           | Accuracy | F1-Score | AUC-ROC |
|----------------|----------|----------|---------|
| Vision Transformer | 82.98%   | 0.82     | 0.84    |
| ResNet50        | 75.40%   | 0.74     | 0.77    |
| MobileNetV2     | 71.67%   | 0.70     | 0.74    |
| Vanilla CNN     | 35.56%   | 0.33     | 0.50    |

## 🛠️ Tools & Libraries

- Python, TensorFlow, Scikit-learn
- Jupyter Notebook, Matplotlib, Seaborn

## 💡 Installation & Usage

```bash
git clone https://github.com/your-username/Human_Action_Recognition_DL.git
cd Human_Action_Recognition_DL
pip install -r requirements.txt
jupyter notebook
```
