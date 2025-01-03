
# Social Media Link Prediction

This project focuses on predicting links (relationships or connections) in social media networks, using a dataset provided during a Facebook recruiting competition. The data represents a snapshot of real-world social network interactions, likely sourced from Instagram.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Installation and Setup](#installation-and-setup)
- [File Descriptions](#file-descriptions)
- [Usage Instructions](#usage-instructions)
- [Acknowledgements](#acknowledgements)

## Project Overview
The goal of this project is to predict whether a link (connection) exists between two users in a social media network based on various features. The project employs:
- Exploratory Data Analysis (EDA)
- Feature engineering
- Machine learning models to perform link prediction.

## Features
- Analysis of social media network data using EDA techniques.
- Featurization of user connections to derive meaningful insights.
- Implementation of machine learning models for link prediction.
- Use of real-world social network data for practical analysis.

## Installation and Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Social-Media-Link-Prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Social-Media-Link-Prediction
   ```
3. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```
   (Note: Ensure the `requirements.txt` file is added if missing.)

4. Open the Jupyter notebooks in the environment of your choice:
   ```bash
   jupyter notebook
   ```

## File Descriptions
- **`FB_EDA.ipynb`**: Contains exploratory data analysis on the dataset, providing insights into the structure and relationships within the data.
- **`FB_featurization.ipynb`**: Covers feature engineering, transforming raw data into formats suitable for machine learning models.
- **`FB_Models.ipynb`**: Implements various machine learning models to predict social media links.
- **`README.md`**: This documentation file.

## Usage Instructions
1. Begin with `FB_EDA.ipynb` to understand the dataset and perform initial analysis.
2. Proceed to `FB_featurization.ipynb` for feature engineering and data preparation.
3. Finally, use `FB_Models.ipynb` to train and evaluate machine learning models for link prediction.

## Acknowledgements
- Dataset provided by Facebook as part of a recruiting competition.
- The project is inspired by challenges in social network analysis and machine learning.

---

Feel free to contribute by submitting issues or pull requests.
