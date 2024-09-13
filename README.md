# Suicidal Text Detection

## Description
This project aims to detect suicidal ideation in text data using deep learning techniques. The dataset is preprocessed and then used to train a neural network model to classify text as either indicative of potential suicide or not.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Model](#model)
- [Contributing](#contributing)

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/greatwhite9/suicidal-text-detection.git
    ```
2. Navigate to the project directory:
    ```bash
    cd suicidal-text-detection
    ```

## Dataset
1. Suicide_Ideation_Dataset(Twitter-based): Given in project structure
2. Suicide_Detection: [Download from here](https://www.kaggle.com/datasets/nikhileswarkomati/suicide-watch)

## Usage
1. Open the Jupyter notebook:
    ```bash
    jupyter notebook Suicidal_text_detection_Final.ipynb
    ```
2. Follow the steps in the notebook to preprocess the data, train the model, and evaluate its performance.

## Model
The model is built using Keras with a Sequential architecture, including Embedding and LSTM layers. It is trained on the preprocessed text data and evaluated on a test set.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
