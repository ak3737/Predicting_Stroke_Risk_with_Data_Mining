# Predicting the Risk of Stroke Using Data Mining

## Abstract

Stroke is a leading global cause of mortality, and early detection is crucial for effective prevention and care. This project leverages data mining techniques to create a predictive model that assesses an individual's stroke risk based on their health and personal metrics. Three classification models, Complement Naïve Bayes, ID3 Decision Tree, and Random Forest, are implemented, and their performance is compared. The project culminates in the development of an interactive application for stroke risk prediction.

---

## Introduction

Stroke, a significant public health concern, requires prompt identification of individuals at risk. The project "Predicting the Risk of Stroke Using Data Mining" addresses this issue by developing a data-driven solution. This README provides an overview of the project, dataset, methodology, and results.

---

## Related Works

The project builds upon prior research in healthcare data mining, particularly in the prediction of cardiovascular diseases and stroke. Key works that influenced this project include [cite relevant research papers and projects].

---

## Project Overview

The primary objective of this project is to create an application that accurately predicts an individual's risk of experiencing a stroke. The project comprises the following key components:

- **Data Collection**: Utilizing a dataset from Kaggle [cite dataset], which includes essential health and personal attributes.

- **Data Preprocessing**: Preparing the dataset by handling missing values, converting attributes, and preparing it for model training.

- **Classification Models**: Implementing three classification models—Complement Naïve Bayes, ID3 Decision Tree, and Random Forest—to predict stroke risk.

- **Performance Evaluation**: Assessing the models based on various metrics, such as accuracy, precision, recall, and F1-score.

- **Application Development**: Building an interactive application that allows users to input their health metrics and receive a stroke risk prediction.

---

## Dataset

The dataset used for this project contains 5110 observations and 12 attributes, including features like age, hypertension, heart disease, and more. The "stroke" attribute serves as the label, indicating whether a patient experienced a stroke (1) or not (0).

---

### Data Preprocessing

Data preprocessing involved handling missing values, converting categorical attributes into suitable formats, and preparing the dataset for training. Notable steps include discretizing age and BMI, imputing missing values, and encoding categorical variables.

### Classification Models

Three classification models were implemented and evaluated:

- **Complement Naïve Bayes**: Achieved an accuracy of 0.925.

- **ID3 Decision Tree**: Achieved an accuracy of 0.9176.

- **Random Forest**: Achieved the highest accuracy of 0.944.

### Performance Comparison

The models were compared based on accuracy, precision, recall, and F1-score. While Random Forest had the highest accuracy, Complement Naïve Bayes demonstrated better balance in precision and recall.

---

## Results

The project's key findings are as follows:

- Complement Naïve Bayes offers a balanced performance in terms of precision and recall, making it suitable for stroke risk prediction.

- Random Forest achieved the highest accuracy but suffered from overfitting with imbalanced data.

- The application provides a user-friendly interface for predicting stroke risk based on input health metrics.

---

## Usage

To use the stroke risk prediction application:

1. Clone this repository to your local machine.

2. Install the necessary dependencies by running `pip install -r requirements.txt`.

3. Run the application using `python stroke_predictor_app.py`.

4. Input the required health metrics, and the application will provide a stroke risk prediction.

---

## Contributors

- Amina Asghar (amina.asghar-1@ou.edu)
- Nasri Binsaleh (nasri.binsaleh-1@ou.edu)
- Onintsoa Ramananandroniaina (ony@ou.edu)

---

## License

This project is licensed under the [MIT License](LICENSE).

![MIT License](https://img.shields.io/badge/license-MIT-blue)

