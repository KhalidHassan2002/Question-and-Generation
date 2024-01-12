# Question Generation Project

## Overview
This project focuses on generating meaningful and contextually relevant questions from a given text using Natural Language Processing (NLP) algorithms. It involves the application of machine learning models to understand and interpret text, ultimately producing questions that capture key information.

## Project Structure
The project is organized as follows:
- Data Preprocessing: Cleaning and preparing the input text data for NLP algorithms.
- Model Training: Utilizing state-of-the-art NLP models for question generation.
- Evaluation: Assessing the performance of the generated questions against reference questions.
- Example Usage: Demonstrating how to use the trained model for question generation.

## Models
From PKE we used these models to extract keywords:
- TopicRank
- TfIdf
- KPMiner
- FirstPhrases
- MultipartiteRank
- TopicalPageRank
- YAKE
- PositionRank
  
After we combine the results of these algorithms, remove the duplicates, get the keywords, and get the sentence that contains this keyword using ("from nltk.tokenize import sent_tokenize",
"from flashtext import KeywordProcessor"), In the final step, we generate the question.
