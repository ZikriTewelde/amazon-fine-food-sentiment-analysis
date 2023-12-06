# Sentiment Analysis on Amazon Fine Food Reviews using Vader and Roberta Pretrained Model
This project delves into the realm of sentiment analysis, exploring the sentiments expressed in Amazon Fine Food Reviews. Leveraging the power of both Vader, a sentiment analysis tool, and the advanced capabilities of the Roberta pretrained model from Hugging Face, the analysis provides nuanced insights into the emotional tone of user reviews. The [Dataset](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews), sourced from Kaggle, serves as the foundation for this exploration. The entire project is meticulously documented and executed within a Jupyter notebook, offering a comprehensive view of the sentiment analysis process. From data preprocessing to model training and evaluation, every step is dissected to unravel the sentiment behind the words in Amazon's fine food reviews.

<p align="center">
  <img src="sentimentpics/sentiment3.jpeg" alt="Sentiment3" width="350"/>
</p>

## Project Overview

The primary objective of this project is to delve into the sentiments expressed in user reviews of Amazon's fine food products. Leveraging the Vader sentiment analysis tool and a pretrained Roberta model from Hugging Face, we aim to gain comprehensive insights into the emotional tone and subjective feedback present in the reviews.

<p align="center">
  <img src="sentimentpics/sentiment2.jpeg" alt="Sentiment2" width="300"/>
</p>

## Table of Contents

1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Prerequisites](#prerequisites)
4. [Getting Started](#getting-started)
5. [Code Structure](#code-structure)
6. [Data Preparation and Exploration](#data-preparation-and-exploration)
7. [Natural Language Processing Techniques](#natural-language-processing-techniques)
8. [Vader Sentiment Analysis](#vader-sentiment-analysis)
9. [Roberta Pretrained Model](#roberta-pretrained-model)
10. [Results and Visualizations](#results-and-visualizations)
11. [Insights and Conclusions](#insights-and-conclusions)
12. [Contributing](#contributing)
13. [License](#license)

## Introduction

In the Jupyter Notebook [sentiment analysis.ipynb](sentiment%20analysis.ipynb), we embark on a comprehensive journey through the world of sentiment analysis. From loading and exploring the dataset to employing advanced NLP techniques and comparing the outcomes of Vader and a state-of-the-art Roberta model, the notebook provides a step-by-step guide to understanding the sentiment landscape of Amazon Fine Food Reviews.

## Dataset

The dataset, obtained from Kaggle, encompasses fine food reviews from Amazon spanning over a decade. Comprising approximately 500,000 reviews up to October 2012, the dataset includes diverse information such as product details, user information, ratings, and the actual textual content of the reviews.

## Prerequisites

Before diving into the analysis, make sure you have the following dependencies installed:

- Python
- pandas
- numpy
- matplotlib and seaborn
- nltk
- Jupyter Notebook
- Vader
- Hugging Face Transformers
- pytorch

## Getting Started

1. **Clone the repository:**

   ```bash
   git clone https://github.com/ZikriTewelde/amazon-fine-food-sentiment-analysis.git
   cd amazon-fine-food-sentiment-analysis
   pip install -r requirements.txt
Install the required dependencies:

## Running the Jupyter Notebook

To run the sentiment analysis Jupyter Notebook locally, follow these steps:

1. Open and run the Jupyter Notebook:

   ```bash
   jupyter notebook sentiment%20analysis.ipynb


## Code Structure

- `sentiment analysis.ipynb`: The main Jupyter Notebook containing the entire analysis code.
- `requirements.txt`: A list of dependencies required for the project.

## Data Preparation and Exploration

The notebook begins with loading the dataset, providing insights into its structure, and sampling a subset for efficient processing.

## Natural Language Processing Techniques

Foundational NLP techniques are explored, including tokenization, part-of-speech tagging, named entity recognition, and chunking.

## Vader Sentiment Analysis

Utilizing the powerful Vader sentiment analysis tool, we gauge the sentiments present in the fine food reviews. A comprehensive analysis is conducted, including visualizations of the compound, positive, neutral, and negative scores.

## Roberta Pretrained Model

To enhance sentiment analysis, we leverage a pretrained Roberta model from Hugging Face. This step involves encoding the text and obtaining sentiment scores, offering a more sophisticated approach to sentiment classification.

## Results and Visualizations

The notebook encompasses various visualizations, including sentiment distributions, model predictions, and comparative analyses between Vader and the Roberta model.

## Insights and Conclusions

The conclusion section synthesizes the findings, highlights key insights, and reflects on potential areas for further exploration and improvement.

## Contributing

Feel free to contribute to the project! Whether you identify areas for improvement, discover new insights, or want to add features, open an issue or submit a pull request.

## License

This project is licensed under the MIT License. Your contributions are welcome, and the project encourages collaboration for continuous improvement.

