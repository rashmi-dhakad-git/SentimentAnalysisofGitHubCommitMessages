# SentimentAnalysisofGitHubCommitMessages

# Project : Sentiment Analysis of GitHub Commit Messages

## Overview

This project leverages Azure Machine Learning Studio and Python SDK v2 to perform sentiment analysis on GitHub commit messages stored in Azure Blob Storage. The analysis aims to extract insights from commit messages, providing a deeper understanding of the emotional tone associated with different authors and repositories over time.

## Project Structure

- **Notebooks:** The `notebooks` directory contains Jupyter Notebooks used for various analyses, including data exploration, sentiment analysis, and visualization. Notebooks are executed in Azure Machine Learning Studio.

- **Data:** The `data` directory holds the dataset used for analysis. GitHub commit messages are stored in Azure Blob Storage.

## Analysis Highlights

1. **Sentiment Distribution:**
   - Visualize the distribution of sentiment scores across all commit messages stored in Azure Blob Storage.

2. **Author-Specific Sentiment:**
   - Explore how sentiment varies across different authors. A boxplot shows the distribution of sentiment scores for each contributor.
3. **Repository-Specific Sentiment:**
   - Investigate sentiment trends specific to different repositories. Another boxplot illustrates the emotional tone associated with each project.

## Getting Started

1. **Azure ML Studio Setup:**
   - Ensure you have access to Azure ML Studio and have set up the required compute resources for running Jupyter Notebooks.

2. **Azure Blob Storage Integration:**
   - GitHub commit messages are stored in Azure Blob Storage. Configure your Azure Blob Storage account credentials in the notebook for seamless data access.

3. **Environment Setup:**
   - Install the necessary dependencies, including the Azure ML Python SDK v2 and NLTK. Use the `%pip` magic command for installations.
4. **Run Notebooks:**
   - Execute the Jupyter Notebooks in the `notebooks` directory in Azure Machine Learning Studio to perform sentiment analysis and visualize results.

