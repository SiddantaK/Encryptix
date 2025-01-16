# Encryptix

## Movie Genre Classification

This repository contains a machine learning project for classifying movie genres using the [Genre Classification Dataset (IMDB)](https://www.kaggle.com/datasets/hijest/genre-classification-dataset-imdb). The project explores text-based movie metadata, trains classification models, and evaluates their performance to predict genres.

### Dataset Information

The dataset, sourced from Kaggle, includes metadata from IMDB movies. The key features are as follows:

- **Movie Name**: Title of the movie.
- **Director**: Name of the movie's director.
- **Actors**: List of the main actors.
- **Genres**: One or more genres associated with the movie (e.g., Action, Comedy, Drama).
- **Plot**: A brief description of the movie's storyline.
- **Language**: Language in which the movie was made.
- **Country**: Country of production.
- **Year**: Release year of the movie.

#### Dataset Size

- Total records: 54086 movies
- Multi-label genres: Movies can belong to multiple genres simultaneously.

## SMS Spam Detection

A machine learning project for classifying SMS using the [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset/data). The SMS Spam Collection is a set of SMS tagged messages that have been collected for SMS Spam research. It contains one set of SMS messages in English of 5,574 messages, tagged according being ham (legitimate) or spam.

This project demonstrates the use of machine learning models to classify spam messages using an imbalanced dataset. The dataset is first balanced using the SMOTE (Synthetic Minority Over-sampling Technique) to handle the class imbalance. Multiple machine learning models such as Naive Bayes, Logistic Regression, and Support Vector Machine (SVM) are trained, evaluated, and compared.

## Credit Card Transactions Fraud Detection Dataset

This project addresses the problem of fraud detection in credit card transactions using machine learning techniques. The data is highly imbalanced, with only a small percentage of transactions being fraudulent. Techniques such as SMOTE are used to balance the dataset, ensuring that models are trained on a more representative sample. [Credit Card Transactions Fraud Detection Dataset](https://www.kaggle.com/datasets/kartik2112/fraud-detection)

## Handwritten Text Generation

This repository contains a deep learning model designed to generate handwritten text images from textual descriptions using a **Generative Adversarial Network (GAN)** approach. The model consists of a **generator** and a **discriminator** trained on a custom dataset of handwritten text images [Handwriting Recognition](https://www.kaggle.com/datasets/landlord/handwriting-recognition).

## Features

- **Generator**: Takes textual input (e.g., a label or description) and noise to generate realistic handwritten text images.
- **Discriminator**: Evaluates whether the generated images are real or fake, helping to train the generator.
