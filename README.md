# Machine-Learning-Project-Text-Classification-using-Naive-Bayes
Text classification project using Naive Bayes and CountVectorizer.


# Text Classification using Naive Bayes

## Project Overview

This project focuses on **Text Classification using the Naive Bayes algorithm**. The main goal is to classify text into different categories based on the words present in the text.

In this project, we use **Multinomial Naive Bayes** along with **CountVectorizer** to convert text data into numerical features and classify the text.

## Dataset

The dataset contains text data divided into four categories:

* **Technology**
* **Sports**
* **Politics**
* **Entertainment**

Each record contains a short sentence or statement along with its corresponding category.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Naive Bayes
* CountVectorizer

## Project Steps

### 1. Importing Libraries

First, we import the required Python libraries such as Pandas, NumPy, Matplotlib, and Scikit-learn.

### 2. Loading the Dataset

The dataset is loaded into Python so that we can process and analyze the text data.

### 3. Splitting the Data

The dataset is divided into **80% training data** and **20% testing data**.

The training data is used to train the model, while the testing data is used to evaluate its performance.

### 4. Text Preprocessing

Since machine learning models work with numerical data, we use **CountVectorizer** to convert the text into numerical features based on word counts.

### 5. Training the Model

We use the **Multinomial Naive Bayes** algorithm to train the classification model.

It works well with text data where features are based on word counts or frequencies.

### 6. Making Predictions

After training the model, we use the test data to predict the category of each text.

### 7. Evaluating the Model

The model is evaluated using:

* **Accuracy Score**
* **Confusion Matrix**

These metrics help us understand how well the model performs and where it makes incorrect predictions.

### 8. Prediction on Unseen Data

Finally, we test the model with new text that was not included in the training or testing data. This helps check whether the model can correctly classify new sentences.

## Model Used

**Multinomial Naive Bayes**

Multinomial Naive Bayes is commonly used for text classification because it works well with discrete features such as word counts and word frequencies.

## Results

The model was able to classify text into the four categories:

**Sports, Technology, Politics, and Entertainment.**

The confusion matrix helps visualize both correct and incorrect predictions made by the model.

## Conclusion

This project demonstrates how **Naive Bayes can be used for text classification**. By converting text into numerical features using CountVectorizer, we can train a machine learning model to classify text into different categories.

The project also shows the complete machine learning workflow, from **loading and preprocessing data to training, prediction, and model evaluation**.
