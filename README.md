# AnomalyDetection_DataMining
Data Mining Assingment 03

# Credit Card Fraud Detection with Transformer Autoencoder

This repository contains code for training a Transformer Autoencoder model for credit card fraud detection.

## Overview

The Transformer Autoencoder model is trained on credit card transaction data to reconstruct normal transactions and detect anomalies, which could potentially be fraudulent transactions.

## Usage

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/credit-card-fraud-detection.git
    cd credit-card-fraud-detection
    ```

2. **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

3. **Download the dataset:**

    You need to provide your own credit card transaction dataset in CSV format. Place the dataset in the root directory of the repository and name it `creditcard.csv`.

4. **Training the model:**

    Run the training script to train the Transformer Autoencoder model:

    ```bash
    python train.py
    ```

5. **Evaluation:**

    After training, the script will output evaluation metrics and detect anomalies in the dataset.

6. **Adjustment and customization:**

    Feel free to adjust the model architecture, hyperparameters, and data preprocessing steps according to your specific requirements.

## File Structure


├── README.md
├── train.py # Script for training the model
├── requirements.txt # List of Python dependencies
├── creditcard.csv # Dataset (not included, you need to provide your own)
├── model.py # Model definitions (Autoencoder, Generator, Discriminator)
└── utils.py # Utility functions (metrics calculation, anomaly detection)


## Requirements

- Python 3.6+
- PyTorch
- pandas
- scikit-learn
- matplotlib

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
