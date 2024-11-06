
# Saudi Riyal Currency Classifier

## Project Overview
This project uses a Convolutional Neural Network (CNN) to classify Saudi Riyal currency into its various denominations, ranging from 5 SR to 500 SR. It's designed to help automate the process of currency recognition in financial systems.

## Features
- Classification of Saudi Riyal denominations using a CNN.
- Utilizes PyTorch for model building and training.
- Implements image preprocessing for better model performance.

## Technologies
- Python
- PyTorch
- Torchvision
- scikit-learn
- NumPy
- PIL for image handling
- Matplotlib for visualization

## Dataset
The model is trained on a balanced dataset consisting of images for the sixth issue of the Saudi Arabian currency banknotes. The dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/gfbati/alfloos/data).

## Setup and Installation
Clone the repository and install the required Python packages:
```bash
git clone <repository-url>
cd <repository-directory>
pip install -r requirements.txt
```

## Model Architecture
The CNN model includes three convolutional layers with batch normalization and max pooling, followed by two fully connected layers. It is trained using the Adam optimizer with a CrossEntropy loss function.

## Results
The model achieves high accuracy in classifying the Saudi Riyal denominations, with detailed performance metrics available in the final report.

## Contributing
Contributions to the project are welcome. Please fork the repository, make your changes, and submit a pull request.


## Acknowledgements
Thank you to all contributors and Umm Al-Qura University's Computer Science & Artificial Intelligence Department for their support in this project.
