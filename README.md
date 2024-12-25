# Algorithmic Symphony: Harmonizing Machine Learning Models Across Diverse Datasets for Performance Evaluation and Comparison

## Introduction

This project, "Algorithmic Symphony," evaluates and compares the performance of various machine learning models across different datasets. The goal is to determine the effectiveness and robustness of four popular classification models: Random Forest, Logistic Regression, Support Vector Classifier (SVC), and K-Nearest Neighbors (KNN).

## Team Members
- [Adithya Krishna S](https://github.com/quark365)
- [B Manish Reddy](https://github.com/Manish-2458)
- [Sreeram R](https://github.com/SreeramRajeev)
- [Avishek Rauniyar](https://github.com/Avishek8136)

## Datasets

1. **Social Well Being Dataset:**
   - Records: 1103
   - Attributes: 10 (7 numerical, 3 categorical)
   - Target: Dominant emotional state (e.g., Happiness, Sadness, Anger, etc.)

2. **Obesity Dataset:**
   - Records: 2100
   - Attributes: 17 (8 numerical, 9 categorical)
   - Target: Obesity levels (Underweight, Normal, Overweight, etc.)

3. **Wine Quality Dataset:**
   - Records: 1143
   - Attributes: 13 numerical
   - Target: Quality score (0-10)

4. **Phishing Email Detection Dataset:**
   - Records: Varies
   - Attributes: 2 (Email Text, Email Type)
   - Target: Email Type (Phishing or Safe)

## Problem Statement

The goal of this project, **Algorithmic Symphony**, is to assess and compare the performance of four widely used machine learning classification algorithms (Random Forest, Logistic Regression, Support Vector Classifier, and K-Nearest Neighbors) across a variety of datasets. This comparison will help determine the strengths and weaknesses of each model in terms of accuracy, robustness, and adaptability to different types of data.

The primary challenge is to:
- Evaluate how each machine learning model handles diverse datasets with varying attributes, such as numerical, categorical, and text data.
- Identify which model consistently performs best across multiple datasets, as well as which models may need specific tuning or adjustments to optimize their performance.
- Provide insights into the suitability of each model for different types of real-world applications, such as predicting emotional states, obesity risk, wine quality, and phishing email detection.

This project aims to provide a comprehensive understanding of machine learning model behaviour, offering valuable insights for selecting appropriate algorithms for specific tasks and datasets.

## Methodology

1. **Data Analysis:** Detailed examination of each dataset.
2. **Data Preprocessing:** Handling missing values, encoding categorical data, and text preprocessing.
3. **Model Training:** Training Logistic Regression, Random Forest, SVC, and KNN models on each dataset.
4. **Evaluation:** Comparing the accuracy of each model on different datasets.

## Results

- **Social Well Being Dataset:**
  - Random Forest: 98%
  - Logistic Regression: 53%
  - SVC: 77%
  - KNN: 95%

- **Obesity Dataset:**
  - Random Forest: 93%
  - Logistic Regression: 88%
  - SVC: 87%
  - KNN: 81%

- **Wine Quality Dataset:**
  - Random Forest: 68%
  - Logistic Regression: 64%
  - SVC: 66%
  - KNN: 56%

- **Phishing Email Detection Dataset:**
  - Random Forest: 95%
  - Logistic Regression: 95%
  - SVC: 93%
  - KNN: 76%

## Conclusion

- **Random Forest:** Most consistent and high-performing model across different datasets.
- **Logistic Regression:** Stable but often outperformed by other models.
- **SVC:** Strong performance but can be inconsistent with certain datasets.
- **KNN:** Performance varies significantly, best for datasets where its assumptions hold true.

## Final Note

For most applications, Random Forest is the preferred model due to its high accuracy and adaptability.

## How to Collaborate

We welcome contributions from the community! Follow these steps to collaborate:

1. **Fork the Repository:**
   - Click the "Fork" button at the top right corner of this repository's page.

2. **Clone Your Fork:**
   - Open your terminal and run:
     ```sh
     git clone https://github.com/your-username/algorithmic-symphony.git
     ```
   - Replace `your-username` with your GitHub username.

3. **Create a Branch:**
   - Navigate to your project directory:
     ```sh
     cd algorithmic-symphony
     ```
   - Create a new branch for your feature or bug fix:
     ```sh
     git checkout -b feature-name
     ```
   - Replace `feature-name` with a descriptive name for your branch.

4. **Make Changes:**
   - Make your changes to the project files.
   - Stage your changes:
     ```sh
     git add .
     ```
   - Commit your changes with a descriptive message:
     ```sh
     git commit -m "Add feature or fix description"
     ```

5. **Push Your Changes:**
   - Push your branch to your forked repository:
     ```sh
     git push origin feature-name
     ```

6. **Create a Pull Request:**
   - Go to the original repository on GitHub and click the "New Pull Request" button.
   - Select your fork and the branch you just pushed.
   - Provide a description of your changes and submit the pull request.

7. **Code Review:**
   - Your pull request will be reviewed by the maintainers.
   - Make any requested changes and push them to your branch.
   - Once approved, your changes will be merged into the main repository.

## Direct Links to Notebooks and Resources

- [Obesity/CVD Risk Notebook](https://github.com/Avishek8136/Algorithmic-Symphony/blob/main/Obesity%20or%20CVD%20Risk%20Prediction/Obesity.ipynb)

- [Phishing Email Classification Notebook](https://github.com/Avishek8136/Algorithmic-Symphony/blob/main/Phishing%20Email%20Classification/phishing_email.ipynb)

- [Social Well Being Notebook](https://github.com/Avishek8136/Algorithmic-Symphony/blob/main/Social%20Well%20Being/Social_Well_Being.ipynb)

- [Wine Quality Classification Notebook](https://github.com/Avishek8136/Algorithmic-Symphony/blob/main/Wine%20Quality%20Classification/Wine%20Quality.ipynb)

Thank you for contributing!
