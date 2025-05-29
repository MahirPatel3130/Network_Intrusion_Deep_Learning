# Network Intrusion Detection Using Deep Learning

## Overview

This repository contains the implementation of a network intrusion detection system using deep learning techniques, specifically designed around the CICIDS-2017 dataset. The system classifies network traffic into benign and various malicious attack types such as Dos/DDoS, PortScan, Botnet, Web Attacks, and Brute Force.

## Contents

* `projectcs179-2.ipynb`: The main Jupyter Notebook containing the entire implementation pipeline from data preprocessing to model training and evaluation.

## Requirements

* Python 3.x
* PyTorch
* pandas
* NumPy
* scikit-learn
* imbalanced-learn
* matplotlib

*(Note: All libraries are pre-installed in Google Colab, but ensure to verify the runtime environment.)*

## Running the Project on Google Colab

Follow these steps to reproduce the results using Google Colab:

1. **Access and Copy the Colab Notebook**

   * [Click here](https://colab.research.google.com/drive/1cRktoDsjCEUolQL5vpRR73VX3F6xrssZ?usp=sharing) to access the notebook.
   * Once opened, go to `File → Save a copy in Drive` to create your own editable copy.

2. **Set Up GPU Runtime**

   * Navigate to `Runtime → Change runtime type`.
   * Select `GPU` from the hardware accelerator dropdown (preferably NVIDIA T4 GPU).
   * Click `Save`.

3. **Run the Notebook**

   * Execute each cell sequentially from the top to the bottom (`Runtime → Run all`).

## Expected Results

Upon successful execution, the notebook will:

* Display preprocessing steps, class distribution adjustments, and feature scaling.
* Train a deep neural network model with early stopping and focal loss.
* Show accuracy and loss metrics over training epochs.
* Provide classification reports and evaluation metrics clearly summarizing model performance.

## Contributions

Feel free to fork this repository, open issues, or submit pull requests if you have suggestions or improvements.

## License

This project is licensed under the MIT License.
