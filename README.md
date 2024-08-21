# Amazon Product Data Analysis

## Project Overview

This project involves analyzing Amazon product review data to extract meaningful insights and trends. The dataset used for this analysis is called `reference_dataset_for_beats_externship` and contains information about product reviews, including various attributes such as ratings, review content, and helpful counts.

## Dataset

The dataset includes the following columns:
- `review_id`: Unique identifier for the review
- `product_id`: Unique identifier for the product
- `title`: Title of the review
- `author`: Author of the review
- `rating`: Rating given by the reviewer
- `content`: Text content of the review
- `timestamp`: Date and time of the review
- `profile_id`: Profile identifier of the reviewer
- `is_verified`: Whether the review is verified
- `helpful_count`: Number of people who found the review helpful
- `product_attributes`: Attributes of the product

## Objectives

The primary goals of this project are:
1. **Exploratory Data Analysis (EDA)**: To understand the distribution and relationships within the data.
2. **Sentiment Analysis**: To analyze the sentiment of the review content.
3. **Correlation Analysis**: To investigate correlations between various features such as ratings and helpful counts.
4. **Skewness Analysis**: To assess the skewness of numerical features and apply necessary transformations.

## Installation

To run this analysis, you'll need to have Python installed along with the necessary libraries. You can install the required libraries using `pip`:

```bash
pip install pandas numpy matplotlib seaborn nltk textblob
