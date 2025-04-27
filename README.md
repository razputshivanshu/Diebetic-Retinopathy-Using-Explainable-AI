# Diabetic Retinopathy Detection - Explainable AI Project

A deep learning project to detect Diabetic Retinopathy from retinal images using Convolutional Neural Networks (CNNs) integrated with Explainable AI (XAI) techniques. The model not only predicts the disease stage but also visually highlights important regions influencing the decision.


## Features

- Detects Diabetic Retinopathy from retinal fundus images.

- Implements Explainable AI techniques (Grad-CAM, LIME) for visual interpretation.

- Improves transparency and trust in AI-based diagnosis.

- Designed to assist ophthalmologists in early and accurate detection.

## Setup

1. Clone the Repo
```
git clone https://github.com/razputshivanshu/Diebetic-Retinopathy-Using-Explainable-AI.git
cd Diebetic-Retinopathy-Using-Explainable-AI

```
2. Create a Virtual Environment (optional but recommended)
```
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

```
3. Install Required Packages
```
pip install -r requirements.txt
```
4. Run the Notebook Open model_file.ipynb in Jupyter Notebook or VS Code and run all cells to train and visualize the results.
```
Diebetic-Retinopathy-Using-Explainable-AI/
├── model_file.ipynb
├── README.md
├── requirements.txt
└── (Saved model files / Grad-CAM outputs)

```

## Technologies Used
- Python
- TensorFlow / Keras
- OpenCV
- Matplotlib
- Grad-CAM, LIME (for Explainability)