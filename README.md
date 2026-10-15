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

## AI Assistance & Tooling
During the development of this project in October 2026, **Google Gemini 3** was utilized as a pair-programming assistant to enhance productivity. Specifically, the AI was used for:
*   Brainstorming ideas and discussing core ML concepts.
*   Debugging issues and optimizing code segments.
*   Generating specific code snippets (code generation).
*   Structuring and generating this README documentation.

*Note: All AI-generated suggestions and code were thoroughly reviewed, tested, and manually integrated to ensure correctness and alignment with the project's goals.*

## Repository Structure
*   `data/`: Directory where the datasets are stored (ignored via `.gitignore` to prevent uploading large files).
*   `notebooks/`: Contains the Jupyter Notebooks with all the source code, analysis, and results (e.g., `01_ebay_auctions_analysis.ipynb`, `02_cifar10_image_classification.ipynb`).
*   `reports/`: Contains the full project report in PDF format in greek (will be updated) (`ml_project_presentation.pdf`).
