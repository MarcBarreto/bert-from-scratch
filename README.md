# Bert From Scratch

## Table of Contents
1. [Introduction](#introduction)
2. [Project Structure](#project-structure)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Classes](#classes)
6. [Model Training and Evaluation](#model-training-and-evaluation)
7. [License](#license)

## Introduction
This project demonstrates building the BERT (Bidirectional Encoder Representations from Transformers) model from scratch. It includes a Jupyter notebook designed to be executed on Google Colab, where various components of BERT are implemented as separate classes, followed by training and evaluation of the model.

## Project Structure
The project is organized as follows:
```sh
bert-from-scratch
┣ 📜 scratch.ipynb
┗ 📜 README.md
┗ 📜 LICENSE
```

## Installation
To run this project, you need to have Google Colab set up. Follow the instructions below to get started:

1. **Open Google Colab**: Go to [Google Colab](https://colab.research.google.com/).

2. **Upload the Notebook**:
   - Click on `File` > `Upload notebook`.
   - Choose the `scratch.ipynb` file from your local machine.

3. **Set Up the Environment**:
   - Ensure you have a Google account to save and execute the notebook.

## Usage
To use the BERT model built from scratch, follow these steps:

1. **Execute the Notebook**:
   - Run each cell in the `scratch.ipynb` notebook sequentially.
   - The notebook includes the following steps:
     - Implementation of BERT components
     - Model training
     - Model evaluation

## Classes
The following classes are implemented in the notebook:

- **Embedding Class**: Handles the embedding of input tokens.
- **ScaledDotProductAttention**: Implements the attention mechanism.
- **MultiHeadAttention Class**: Combines multiple attention heads.
- **PosWiseFeedForward Class**: Implements the position-wise feed-forward network.
- **Encoder_layer Class**: Represents a single encoder layer in the BERT model.
- **BERT Class**: Combines all components to form the complete BERT model.

## Model Training and Evaluation
The notebook includes sections for training and evaluating the BERT model. It covers:

- **Training**: Steps to train the BERT model from scratch using a suitable dataset.
- **Evaluation**: Methods to evaluate the performance of the trained model.

## License
This project is licensed under the MIT License. See the [LICENSE](https://opensource.org/licenses/MIT) file for more information.

---

Feel free to explore the notebook and experiment with different configurations to see how the model performs!

