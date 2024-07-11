# Zillow Listings Text Analysis

This repository contains a Python script for preprocessing and analyzing text data from Zillow real estate listings. The script performs various text-cleaning tasks, tokenizes the text, and conducts frequency analysis to extract useful insights.

## Features

- **Text Preprocessing**: Removes punctuation, stopwords, numeric characters, and short words.
- **Tokenization**: Splits the cleaned text into individual tokens (words).
- **Frequency Analysis**: Counts the frequency of words and plots the most common terms.
- **Vectorization**: Converts text data into a vectorized format for further analysis.
- **Restriction Analysis**: Identifies and counts the presence of specific restriction-related terms in the listings.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- gensim
- scikit-learn
- nltk
- scipy

## Usage

1. Ensure all required libraries are installed.
2. Set the correct file path and load your Zillow CSV file.
3. Run the script to preprocess the text data, tokenize it, and perform frequency analysis.
4. Analyze the output to gain insights from the Zillow listings.

## Output

- Cleaned text data appended to the original DataFrame.
- Frequency plots of the most common terms.
- CSV file (`Restrictions.csv`) containing counts of specific restriction-related terms for each listing.

## License

This project is licensed under the MIT License.
