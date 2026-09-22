#  ML Mini-Projects

A collection of independent machine learning projects covering classification, fraud detection, computer vision, and generative modeling — built to practice and demonstrate core ML workflows: data preprocessing, feature engineering, model building, and evaluation.

---

##  Projects in This Repository

| Project | Type | Core Technique |
|---|---|---|
| [Binary Image Classification (CNN)](Binary_image_classification_CNN/chest) | Computer Vision | Convolutional Neural Network |
| [Churn Prediction](Churn_prediction_MLP) | Classification | Multi-Layer Perceptron (MLP) |
| [Fraud Detection](Fraud_detection) | Classification | Traditional ML models |
| [Credit Card Fraud Detection (ANN)](Credit%20Card%20Fraud%20Detection%20ANN.ipynb) | Classification | Artificial Neural Network |
| [Deformable CNN](Deformable_CNN.ipynb) | Computer Vision | Deformable Convolutions |
| [Digit Recognition](DigitRecognition.ipynb) | Computer Vision | CNN / Classic ML |
| [GAN Content Generation](GAN_ContentGeneration.ipynb) | Generative Modeling | Generative Adversarial Network |

---

## Project Details

### 1. Binary Image Classification (CNN)
Trains a Convolutional Neural Network to classify medical/chest images into two classes.
**Dataset:** *[e.g. chest X-ray dataset — fill in]*
**Key result:** *[e.g. accuracy/F1-score achieved — fill in]*

### 2. Churn Prediction (MLP)
Predicts customer churn using a Multi-Layer Perceptron neural network on customer behavior/subscription data.
**Techniques:** Feature engineering, MLP architecture, evaluation via accuracy/precision/recall.

### 3. Fraud Detection
Applies classic ML classification techniques to detect fraudulent transactions.
**Techniques:** Data preprocessing, handling class imbalance, model evaluation.

### 4. Credit Card Fraud Detection (ANN)
Builds an Artificial Neural Network to flag fraudulent credit card transactions — a classic imbalanced-classification problem.
**Key challenge addressed:** Class imbalance between fraud vs. non-fraud transactions.

### 5. Deformable CNN
Explores deformable convolutions — a CNN variant that adapts its receptive field to better capture spatial variation in image data, compared to standard convolutions.

### 6. Digit Recognition
Classic handwritten digit classification (MNIST-style), used to demonstrate an end-to-end image classification pipeline.

### 7. GAN Content Generation
Implements a Generative Adversarial Network (GAN) to generate synthetic content, exploring generator/discriminator training dynamics.

---

## Tech Stack

- **Language:** Python
- **Core Libraries:** Pandas, NumPy, Scikit-learn
- **Deep Learning:** *[TensorFlow/Keras or PyTorch — specify which you used]*
- **Environment:** Jupyter Notebook

---

## How to Use

1. Clone the repository:
```bash
   git clone https://github.com/janhavi1027/ML-Projects.git
   cd ML-Projects
```
2. Install dependencies:
```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   # add tensorflow / torch depending on which notebooks you run
```
3. Open any notebook in Jupyter and run through the cells:
```bash
   jupyter notebook
```

---

##  Possible Improvements

- [ ] Add a dedicated README inside each project folder with dataset source, approach, and results
- [ ] Add a `requirements.txt` per project (or one shared file) so dependencies are reproducible
- [ ] Include sample output visuals (confusion matrices, generated GAN samples, accuracy/loss curves) directly in this README
- [ ] Move the loose root-level notebooks (Credit Card Fraud, Deformable CNN, Digit Recognition, GAN) into their own folders for consistency with the other projects

---
