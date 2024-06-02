# Suicidal Text Detection

## Description
This project aims to detect suicidal ideation in text data, specifically from Twitter posts, using deep learning techniques. The dataset is preprocessed and then used to train a neural network model to classify text as either indicative of potential suicide or not.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Dataset](#dataset)
- [Model](#model)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/suicidal-text-detection.git
    ```
2. Navigate to the project directory:
    ```bash
    cd suicidal-text-detection
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Open the Jupyter notebook:
    ```bash
    jupyter notebook Suicidal_Text_Detection_DL_Project.ipynb
    ```
2. Follow the steps in the notebook to preprocess the data, train the model, and evaluate its performance.

## Project Structure
- `Suicidal_Text_Detection_DL_Project.ipynb`: Jupyter notebook containing the project code.
- `requirements.txt`: List of required packages.

## Dataset
The dataset consists of Twitter posts labeled for suicidal ideation. It is loaded from a CSV file and preprocessed to remove stopwords, punctuations, and numbers, and to perform lemmatization and lowercasing.

## Model
The model is built using Keras with a Sequential architecture, including Embedding and LSTM layers. It is trained on the preprocessed text data and evaluated on a test set.

## Results
The model's performance metrics, such as accuracy, precision, recall, and F1 score, are evaluated and displayed in the notebook.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
