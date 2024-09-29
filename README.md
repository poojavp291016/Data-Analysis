# Data-Analysis
Exploring Text Readability and Word Complexity Metrics in Large Datasets
Overview
This project focuses on analyzing the readability and complexity of large text datasets. By processing text documents, the project computes several key linguistic metrics, such as the percentage of complex words and the average number of words per sentence. The goal is to assess text difficulty and identify trends across different datasets based on these complexity measures.

Key Features
Text Preprocessing: Tokenizes text data, removes stop words, and processes each file to clean the data for analysis.
Word Complexity Analysis: Calculates the percentage of complex words in the text based on word length and syllable count.
Readability Metrics: Computes average words per sentence and overall sentence structure to gauge the readability of the text.
Automated File Processing: Processes multiple text files from a dataset directory, generating detailed readability reports for each file.
Technical Stack
Python: Primary language for the project.
Natural Language Toolkit (NLTK): Used for tokenization, stopword removal, and syllable counting.
Text Metrics:
Complex Word Percentage: Identifies and calculates the percentage of complex words.
Average Sentence Length: Measures the number of words per sentence for readability analysis.
How It Works
Text Cleaning: Each document is tokenized, and stop words are removed.
Complexity Calculation: The program calculates the percentage of words with more than two characters or multiple syllables, treating them as complex.
File-by-File Analysis: Metrics are calculated for each text file, and results are printed, providing insight into the overall complexity and readability of the dataset.
Example Output
For each file, the system prints:

Percentage of Complex Words
Average Number of Words per Sentence
Total Complex Word Count
