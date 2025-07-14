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
 ┣ 📜README.md
 ┣ 📜requirements.txt
```
## 📂 Dataset
Source: Kaggle HAR Dataset
    Dataset is public available, Link provided below due to the size 
Link: https://www.kaggle.com/datasets/meetnagadia/human-action-recognition-har-dataset

Size: 12,000+ RGB images across 15 action categories

Preprocessing: Image resizing, normalization, label encoding, and augmentation

## 🧠 Models Implemented
Vanilla CNN (custom baseline)

MobileNetV2 (transfer learning)

ResNet50 (transfer learning with residual blocks)

Vision Transformer (ViT) (transformer-based model from Hugging Face)

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
## 📸 Visual Results
Top results achived model vision Transformers (VIT) Confusion Matrix and AUC- ROC curve snippets 
<img width="931" height="790" alt="image" src="https://github.com/user-attachments/assets/86a00c09-1b7c-451e-9c3d-f3864ec4b82a" />

AUC-ROC Curve 

<img width="989" height="790" alt="image" src="https://github.com/user-attachments/assets/d8343cc5-7b2f-4e76-ab5b-659d58a04e5e" />

## Models Predictions on unseeen Data screenshot 
<img width="563" height="522" alt="image" src="https://github.com/user-attachments/assets/3fc27338-ea4c-4b47-8bce-8feca505117f" />

## 🙏 Acknowledgements
Supervisor: Prof Mohit Gurg , Dublin Business School
Open Source Dataset : HAR Dataset from Kaggle 
Frameworks: computer vision, python - Tenserflow, Keras 
Community Support: AI/ML forums, Roboflow, Medium
My friends and family for continious support
## 📜 License
This project is for academic research purposes. Attribution required for reuse


