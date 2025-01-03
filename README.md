
# Social Media Link Prediction

This project focuses on predicting links (relationships or connections) in social media networks, using a dataset provided during a Facebook recruiting competition. The data represents a snapshot of real-world social network interactions, likely sourced from Instagram.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Installation and Setup](#installation-and-setup)
- [File Descriptions](#file-descriptions)
- [Featurization Techniques](#featurization-techniques)
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

## Featurization Techniques
To predict links effectively, various features were engineered to represent relationships between nodes (users) in the social network:

1. **Node-Based Features**:
   - **Degree Centrality**: Measures the number of connections a node has.
   - **PageRank**: Quantifies the influence of a node in the network.
   - **Clustering Coefficient**: Indicates the level of interconnectedness of a node's neighbors.

2. **Pair-Based Features**:
   - **Number of Mutual Connections**: Strongly correlates with link formation.
   - **Jaccard Similarity**: Captures the overlap between neighbors of two nodes.
   - **Adamic-Adar Index**: Highlights shared neighbors with fewer overall connections.

3. **Graph-Based Embeddings**:
   - **Node2Vec**: Generates low-dimensional representations of nodes based on graph walks.
   - **Graph Neural Networks (GNNs)**: Produces embeddings by aggregating neighborhood information.

4. **Attribute-Based Features**:
   - **Cosine Similarity**: Measures similarity between user attributes.
   - **Categorical Matches**: Detects common properties, such as shared location or interests.

5. **Temporal Features**:
   - **Interaction Frequency**: The number of interactions between nodes over time.
   - **Time Since Last Interaction**: Captures temporal dynamics in relationships.

6. **Hybrid Features**:
   - Combines multiple feature types to provide a comprehensive representation of potential links.

These features were selected and engineered to enhance the performance of machine learning models in predicting links.

## Usage Instructions
1. Begin with `FB_EDA.ipynb` to understand the dataset and perform initial analysis.
2. Proceed to `FB_featurization.ipynb` for feature engineering and data preparation.
3. Finally, use `FB_Models.ipynb` to train and evaluate machine learning models for link prediction.

## Acknowledgements
- Dataset provided by Facebook as part of a recruiting competition.
- The project is inspired by challenges in social network analysis and machine learning.

---

Feel free to contribute by submitting issues or pull requests.
