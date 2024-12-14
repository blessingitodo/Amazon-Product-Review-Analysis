# Analyzing Amazon Reviews with Python

## Overview
This project focuses on analyzing text reviews using Python. It involves preprocessing data, conducting exploratory data analysis (EDA), visualizing patterns, and potentially applying machine learning techniques to extract insights. The project leverages popular Python libraries like Pandas, Matplotlib, and others for data analysis and visualization.

## Features
- **Data Preprocessing**: Cleaning and preparing the dataset for analysis.
- **Exploratory Data Analysis (EDA)**: Identifying trends, patterns, and outliers in the review data.

## Installation
To run this project, ensure you have Python 3.7 or higher installed. Follow these steps:

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook reviews.ipynb
   ```
2. Run the cells sequentially to:
   - Load the dataset
   - Perform data preprocessing
   - Conduct EDA and visualizations
   - (Optional) Apply machine learning models for sentiment analysis

## Prerequisites
Ensure the following Python libraries are installed:
- Pandas
- NumPy
- datetime
- os
- json (data files were jsonl files)

## File Structure
- `reviews.ipynb`: Main notebook containing the analysis pipeline.
- `data/`: Directory for input datasets.
- `outputs/`: Directory for saving generated visualizations and results.
- `requirements.txt`: List of required Python libraries.

## Dataset
Thanks to McAuley Lab for datasets. Datasets used were the All_beauty, and Magazine_Subscription datasets from the lists of datasets posted.
**Source**: [https://huggingface.co/datasets/McAuley-Lab/Amazon-Reviews-20](https://huggingface.co/datasets/McAuley-Lab/Amazon-Reviews-2023)
**Drive for mount drive**: https://drive.google.com/drive/folders/10K7eSB7m_TAtVBx1L8UhtdoXPoadf7v4

## Results
Key insights and visualizations from the notebook include:
- Trends and patterns in review data
- Relationships between features
- Sentiment polarity (if applicable)

## Future Analysis
Given this is an ungoing project, I plan to expand my analysis into the following: 
- **Visualizations**: Creating plots to enhance understanding of the dataset.
- **Sentiment Analysis (Optional)**: Applying natural language processing (NLP) techniques to determine sentiment polarity.





