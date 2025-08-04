# Sentiment Analysis of Movie Reviews using NLP
## Project Overview
This project demonstrates the application of Natural Language Processing (NLP) to perform sentiment analysis on the IMDB movie review dataset. A pre-trained transformer model was leveraged to classify reviews as either positive or negative, showcasing a modern and highly effective approach to text classification.

## Key Features
- State-of-the-Art NLP Model: Utilized DistilBERT, a distilled version of Google's BERT, from the Hugging Face Transformers library for high-performance sentiment classification.

- Quantitative Evaluation: The model's performance was rigorously evaluated on an unseen test set, achieving 88.1% accuracy.

- Modern NLP Workflow: The project follows a standard industry workflow, including data loading with the datasets library, tokenization, and model inference using a pre-built pipeline.

## Project Structure
- CMENDOZA_FinalProject.ipynb: The main Jupyter Notebook containing all Python code for data loading, preprocessing, model inference, and evaluation.

- CMENDOZA_FinalProject.pdf: A detailed report summarizing the project's introduction, methodology, results, and challenges faced.

## How to Run
1. Setup: Open the .ipynb file in a Jupyter environment like Google Colab or JupyterLab.

2. Install Libraries: Run the first code cell to install the necessary packages:
pip install tensorflow tensorflow-datasets transformers datasets evaluate

3. Execute Cells: Run the notebook cells sequentially from top to bottom to replicate the analysis and results.

## Tech Stack
- Languages: Python

- Data Science & NLP: Hugging Face (Transformers, Datasets, Evaluate), TensorFlow, NumPy, JupyterLab
