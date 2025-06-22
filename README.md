# Handwritten Devanagari OCR Model Training

This repository contains the training and testing notebook for a deep learning model used to recognize handwritten Devanagari characters or words.

## 📁 Files

- `train_test.ipynb`: Main Jupyter Notebook for training and testing the OCR model.

## 🧠 Model

This project utilizes:
- HuggingFace Transformers (likely `TrOCR`)
- PyTorch
- Custom Dataset of handwritten Devanagari characters/words
### 🗃️ Dataset Reference

This project uses or is inspired by the **Indic Handwritten Text Dataset** released by [CVIT, IIIT-Hyderabad](https://cvit.iiit.ac.in/research/projects/cvit-projects/indic-hw-data).

It contains handwritten line-level images and corresponding Unicode text labels for multiple Indian scripts including Devanagari.

🔗 [Visit Dataset Page](https://cvit.iiit.ac.in/research/projects/cvit-projects/indic-hw-data)



## 🛠️ Setup

1. **Clone the repository**
   
2. **Create a virtual environment (optional but recommended)**

3. **Install dependencies**
   pip install -r requirements.txt

4. **Run the notebook**
