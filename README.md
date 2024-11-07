# Grammatical Error Correction Project

This project focuses on analyzing and correcting grammatical errors in text using various Natural Language Processing (NLP) techniques and machine learning models.

## Project Overview

The project involves the following steps:

1. **Data Loading and Preprocessing:** Loading a dataset of ungrammatical and corrected sentences, cleaning the data, and preparing it for analysis and model training.
2. **Exploratory Data Analysis (EDA):** Performing EDA to understand the characteristics of the data, including error type frequencies, sentence length distributions, and common grammatical patterns.
3. **Model Training and Evaluation:** Training different grammatical error correction (GEC) models, such as T5-based models, and evaluating their performance using metrics like BLEU.
4. **Error Analysis and Visualization:** Analyzing common error patterns and visualizing them using techniques like word clouds and frequency distributions.
5. **Grammar Correction with Happy Transformer:** Using the Happy Transformer library to apply the trained model for correcting grammar in new text.

## Dataset

The project uses the "Grammar Correction.csv" dataset, which contains pairs of ungrammatical and corrected sentences.

## Libraries Used

The following libraries are used in this project:

- pandas
- nltk
- matplotlib
- seaborn
- textstat
- Levenshtein
- textblob
- wordcloud
- transformers
- happytransformer
- optuna
- evaluate

## Usage

1. Clone the repository: `git clone <repository_url>`
2. Install the required libraries: `pip install -r requirements.txt`
3. Run the Jupyter Notebook: `jupyter notebook Grammatical_Error_Correction.ipynb`

## Results

The project achieves promising results in grammatical error correction, with the best-performing model achieving a high BLEU score on the test set.

## Future Work

- Explore more advanced GEC models and techniques.
- Fine-tune models on larger and more diverse datasets.
- Develop a user-friendly interface for grammar correction.

## Contributing

Contributions are welcome! Please feel free to open issues or pull requests.

