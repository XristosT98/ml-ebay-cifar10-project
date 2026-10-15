# Machine-Learning-eBay-Auctions-Analysis-CIFAR-10-Classification

This repository contains my project for the "Machine Learning: Methods and Algorithms" course. It consists of two main parts:

## Part A: eBay Auctions Analysis
The goal of the first part is to develop Machine Learning models to predict characteristics of eBay auctions. Specifically, we focus on:
*   **Sales Prediction (Classification):** Predicting whether an item will be sold or not.
*   **Price Prediction (Regression):** Predicting the final sale price for items that are successfully sold.
*   **Competitiveness (Classification):** Predicting the competitiveness of an auction based on the number of bids.

The analysis includes extensive Feature Engineering (e.g., Target Encoding), data splitting (Train/Validation/Test), and the evaluation of multiple machine learning algorithms.

## Part B: CIFAR-10 Image Classification
In the second part, classic Computer Vision techniques are applied to classify images from the CIFAR-10 dataset. 
Our methodology (Pipeline):
1.  **HOG (Histogram of Oriented Gradients):** For feature extraction (shapes, edges) from the images.
2.  **PCA (Principal Component Analysis):** For dimensionality reduction.
3.  **Classification:** Comparing the performance of three algorithms: Support Vector Machine (SVM), k-Nearest Neighbors (k-NN), and Random Forest. We also examine the performance improvement achieved by integrating color information (HOG + Color).

## Technologies
The project was developed in Python and utilizes the following libraries:
*   `scikit-learn`: For implementing and evaluating all Machine Learning algorithms.
*   `pandas` & `numpy`: For data manipulation and analysis.
*   `scikit-image`: For HOG feature extraction.
*   `matplotlib` & `seaborn`: For data visualization.

## Repository Structure
*   `data/`: Directory where the datasets are stored (ignored via `.gitignore` to prevent uploading large files).
*   `notebooks/`: Contains the Jupyter Notebooks with all the source code, analysis, and results (e.g., `Τελελης_ebay_final_3.ipynb`, `Τελέλης_εικόνες_Final_3.ipynb`).
*   `reports/`: Contains the full project report in PDF format (`Παρουσίαση_Τελελης_2.pdf`).
