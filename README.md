# Handwritten Digit Recognition

Recognizes handwritten digits (0-9) from 8x8 pixel images using a Support Vector Machine (SVM) classifier.

## Tools
Python, pandas, NumPy, matplotlib, scikit-learn

## What I did
- Loaded 1,797 digit images stored as 64 pixel values each
- Displayed the images with matplotlib
- Split the data into training and test sets
- Trained an SVM classifier and measured its accuracy
- Compared different kernel, gamma and C settings

## Files
- `02_handwritten_digit_recognition_svm.ipynb`: the full notebook

## Dataset
The scikit-learn handwritten digits dataset (1,797 samples, 64 features, 10 classes). The dataset file is not included in this repository.

## How to run
Install the libraries:

    pip install pandas numpy matplotlib scikit-learn

Then open the notebook in Jupyter and run all cells.
