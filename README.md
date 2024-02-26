# Homework: Text Analysis with spaCy and NLTK

This repository contains a Jupyter Notebook (`hw12.ipynb`) demonstrating the process of text analysis using the Natural Language Processing (NLP) libraries spaCy and NLTK. The project includes punctuation and stop words removal, tokenization, word frequency calculation, and key sentence selection for summarizing text.

## How to Use

To run the `hw12.ipynb` notebook, you need to have Jupyter Notebook or JupyterLab installed in your environment. You can open the notebook in Jupyter and execute the cells sequentially to see the results of the text processing.

## Installation of Required Libraries

Before starting, you need to install the spaCy and NLTK libraries. This can be done using pip:

```
pip install spacy
pip install nltk
```

For spaCy, you also need to download a model for the English language:

```
python -m spacy download en_core_web_sm
```

Don't forget to download the necessary data for NLTK by running the following code in your Python console:

```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
```

## Features

The notebook includes the following text processing steps:

- Removal of punctuation and stop words
- Text tokenization into words and sentences
- Calculation of word frequency
- Determination of sentence weight and selection of key sentences for summary

## License

This project is distributed under the MIT License.
