# Text Summarizer
This repository contains three different techniques for text summarization: Extractive, Abstractive, and BART-based Abstractive summarization. To learn more about these techniques, refer to the following articles:


- [Introduction to Text Summarization](https://medium.com/@catplotlib/in-the-field-of-natural-language-processing-nlp-summarization-plays-a-crucial-role-in-reducing-519af0432d96)
- [Revolutionizing Text Summarization with Abstractive Techniques](https://medium.com/@catplotlib/revolutionizing-text-summarization-with-abstractive-techniques-a-deep-dive-into-abstractive-14014bd54a00)

## Repository Contents
- EX_final.ipynb: Extractive Summarization technique using a pre-trained GloVe model with 100-dimensional word vectors to create sentence vectors. The NLTK package's sent_tokenize function is used for tokenizing text into sentences.
- AB_final.ipynb: Abstractive Summarization technique using a sequence-to-sequence (seq2seq) encoder-decoder architecture to generate summarized text.
- BART_final.ipynb: Abstractive Summarization technique using the pre-trained T5 model to generate a summary of the input text.

## Dataset
The dataset for this project is available [here](https://drive.google.com/drive/folders/151c1Y276AZuV2TZSJ3FzA9WNSva65xae?usp=sharing).

## How to Run
- Go to the dataset link.
- Click on the 'Final NLP' dropdown menu.
- Select "Add Shortcut to Drive" from the menu to add the dataset to your Google Drive.
- Now you can access the dataset from your Google Drive and run all three notebooks using Google Colab.
