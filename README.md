# Hinglish Translator

## Introduction
This project aims to provide a simple yet effective tool for translating English sentences into "Hinglish" – a popular blend of Hindi and English commonly used in informal communication in India. The translator takes English input and provides a Hinglish output, maintaining the essence of both languages.

## Why This Strategy?
We chose a unique approach for Hinglish translation, focusing on the syntactical structure of English and Hindi languages. The strategy involves three key steps:

- **Identifying English Nouns**: Nouns often carry the core meaning in a sentence. By identifying them, we ensure that these key elements are preserved in the translation.

- **Translating Sentence to Hindi**: The entire sentence is translated to Hindi, offering a base that aligns with Hindi syntax and grammar.

- **Replacing Hindi Nouns with English Counterparts**: This step is crucial. It replaces the nouns in the Hindi sentence with their original English versions. This method preserves the sentence's meaning while blending Hindi and English in a way that is authentic to how Hinglish is naturally spoken.

This strategy was chosen because it mimics the natural process of Hinglish formation, where speakers often mix Hindi syntax with key English terms, especially nouns, resulting in a sentence that is relatable and understandable to speakers of both languages.

## Installation
```bash
pip install nltk
pip install googletrans==4.0.0-rc1
```
## Usage
The project is structured into modular functions, each serving a specific part in the translation process. To use the translator, run the test_translation() function and input an English sentence when prompted.

## Project Structure
- **find_nouns**: Identifies nouns in English sentences.
- **translate_to_hindi**: Translates English sentences to Hindi.
- **replace_nouns_with_english:** Replaces Hindi nouns with their English counterparts in the translated sentence.
- **test_translation:** A simple function to test the translation process.
## Contributions
Contributions to enhance the translation accuracy, efficiency, or to add more features are welcome. Please feel free to fork this repository and submit pull requests.
