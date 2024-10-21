# Hugging-Face-Inference

This repository contains a Jupyter Notebook that demonstrates how to perform inference using a pre-trained Named Entity Recognition (NER) model from the Hugging Face Transformers library.

## Overview

The `hf_inference.ipynb` notebook includes the following functionality:

1. Load a pre-trained NER model and tokenizer from a specified path.
2. Define a `perform_ner` function that takes an input text, performs inference using the loaded model, and returns the predicted entities and their confidence scores in a JSON-like format.
3. Provide an example usage of the `perform_ner` function to demonstrate the inference process.

## Usage

1. Clone the repository:
   ```
   git clone https://github.com/your-username/Hugging-Face-Inference.git
   ```

2. Open the Jupyter Notebook `hf_inference.ipynb` and follow the instructions in the notebook.

3. Customize the script to use your own pre-trained NER model and to process your specific input texts.

## Requirements

- Python 3.x
- Jupyter Notebook
- PyTorch
- Transformers library

## Contributions

Contributions to this repository are welcome. If you have any suggestions, bug reports, or additional features you'd like to add, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
