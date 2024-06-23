# Heart Disease Prediction Project 🫀✨

Welcome to the Heart Disease Prediction Project! This project aims to predict the likelihood of heart disease in individuals based on various health parameters using a Logistic Regression model.

## 📑 Table of Contents

- [🔍 Overview](#overview)
- [📊 Dataset](#dataset)
- [⚙️ Installation](#installation)
- [🚀 Usage](#usage)
- [🧠 Model Training](#model-training)
- [📈 Model Evaluation](#model-evaluation)
- [🔮 Prediction](#prediction)
- [🤝 Contributing](#contributing)
- [📜 License](#license)

## 🔍 Overview

This project uses machine learning to predict whether a person has heart disease. The model is trained on a dataset containing various health indicators such as age, sex, cholesterol levels, and more. The goal is to accurately classify individuals as either having heart disease or not.

## 📊 Dataset

The dataset used for this project is `heart_disease_data.csv`, which contains the following columns:

- `age`: Age of the patient
- `sex`: Sex of the patient
- `cp`: Chest pain type
- `trestbps`: Resting blood pressure
- `chol`: Serum cholesterol
- `fbs`: Fasting blood sugar
- `restecg`: Resting electrocardiographic results
- `thalach`: Maximum heart rate achieved
- `exang`: Exercise-induced angina
- `oldpeak`: ST depression induced by exercise relative to rest
- `slope`: The slope of the peak exercise ST segment
- `ca`: Number of major vessels colored by fluoroscopy
- `thal`: Thalassemia
- `target`: Diagnosis of heart disease (1 = disease, 0 = no disease)

## ⚙️ Installation

To run this project locally, you need to have Python installed. Follow these steps to get started:

1. 📥 Clone this repository:

    ```bash
    git clone https://github.com/avishka/heart-disease-prediction.git
    ```

2. 📂 Navigate to the project directory:

    ```bash
    cd heart-disease-prediction
    ```


## 🚀 Usage

1. Ensure you have the dataset `heart_disease_data.csv` in the project directory.
2. Run the Python script to train the model and make predictions.

    Run Heart Disease Predictor.ipynb using jupyter notebook

## 🧠 Model Training

The model is trained using the Logistic Regression algorithm. The dataset is split into training and testing sets. The model is trained on the training set and evaluated on the testing set.

## 📈 Model Evaluation

The model's accuracy is evaluated using the `accuracy_score` metric. Here are the results:

- **Training Accuracy**: 85.12% 📊
- **Testing Accuracy**: 81.97% 📉

## 🔮 Prediction

To make predictions using the trained model, you can provide input data. For example:

```python
input_data = (42,1,2,130,180,0,1,150,0,0,2,0,2)
prediction = model.predict(input_data)

if(prediction[0] == 1):
    print("Diseased Heart 💔")
else:
    print("Healthy Heart ❤️")
```

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

 
