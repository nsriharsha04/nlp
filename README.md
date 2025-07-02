# NLP Demo

This project contains a Jupyter Notebook (`nlp-demo.ipynb`) that demonstrates Natural Language Processing (NLP) techniques using the `spacy` library.

## Notebook Summary

The `nlp-demo.ipynb` notebook serves as a practical demonstration of various Natural Language Processing (NLP) tasks. It utilizes the `spacy` library in Python to process and analyze text. The notebook covers the following key NLP concepts:

*   **Tokenization:** The process of breaking down a text into individual words or "tokens".
*   **Part-of-Speech (POS) Tagging:** Assigning a grammatical category (like noun, verb, adjective) to each token.
*   **Named Entity Recognition (NER):** Identifying and classifying named entities in the text, such as names of people, organizations, and locations.
*   **Lemmatization:** Reducing words to their base or dictionary form for analysis.
*   **Stop Word Removal:** Filtering out common words (like "the", "a", "is") that often don't carry significant meaning.

In essence, the notebook provides a hands-on example of how to use a popular NLP library to extract meaningful information and structure from plain text.

## Getting Started

### Prerequisites

Make sure you have Python and Jupyter Notebook installed on your system.

### Installation

1.  Clone the repository:
    ```bash
    git clone <repository-url>
    cd nlp
    ```
2.  Install the required libraries:
    ```bash
    pip install spacy
    ```
    You may also need to download a `spacy` model:
    ```bash
    python -m spacy download en_core_web_sm
    ```

## Usage

1.  Start the Jupyter Notebook server:
    ```bash
    jupyter notebook
    ```
2.  Open `nlp-demo.ipynb` in your browser and run the cells.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
