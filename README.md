# Sepsis Prediction using LSTM

This repository contains code for predicting sepsis occurrence using an LSTM-based deep learning model. The goal is to predict the occurrence of sepsis as early as possible using time series data from multiple patients, using the [PhysioNet/Computing in Cardiology Challenge 2019 Dataset](https://physionet.org/content/challenge-2019/1.0.0/)

## Table of Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Sepsis is a life-threatening condition that requires early detection and intervention. This project aims to develop a predictive model using long short-term memory (LSTM) neural networks to predict sepsis occurrence in patients. The LSTM model takes into account the time-dependent nature of the data and learns patterns to make predictions.

The project includes data preprocessing steps, such as handling missing values, feature engineering, and data scaling. It also covers the construction of sliding windows to create sequences for training the LSTM model. The model is trained on a subset of patients and evaluated on a separate test set. Performance metrics such as accuracy, precision, recall, and area under the ROC curve are used to assess the model's predictive capabilities.

## Requirements

To run the code in this repository, you'll need the following:

- Python 3.x
- Required Python packages (specified in the `requirements.txt` file)
- Jupyter Notebook or Jupyter Lab (for running the notebooks)

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/msplittgerber/sepsis-shock-prediction.git
   ````
2.	Install the required Python packages:
   
  ```bash
  pip install -r requirements.txt
  ```
4.	Explore the Jupyter notebook in the repository:
o	Covers the preprocessing steps for handling missing values, feature engineering, and scaling the data.
o	Includes the implementation of the LSTM model and training process.
o	Evaluates the trained model on the test set and computes performance metrics.

3.	Modify the code and experiment with different parameters as needed.

## Results

The results of the LSTM-based sepsis prediction model can be found in the results folder. This folder contains saved model weights, evaluation metrics, and visualizations. The evaluation metrics include accuracy, precision, recall, and the ROC curve.

## Contributing

Contributions to this repository are welcome. If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request. We appreciate your contributions.

## License

MIT License

Copyright (c) 2015 Chris Kibble

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
