
# Model-Calibration-Binary-Classification
=======
# **Supervised Learning: Model Calibration for Binary Classification**

## This repository contains my work on model calibration techniques for enhancing the reliability of predicted probabilities in binary classification tasks. The project focuses on applying machine learning techniques to improve prediction accuracy and reliability in real-world datasets.

## **Project Overview**

The goal of this project is to demonstrate the importance of calibration techniques in machine learning models to improve the reliability of their predicted probabilities. The dataset used involves features related to health parameters for predicting anemia status.

------------------------------------------------------------------------

## **Features of the Project**

-   **Dataset:**
    -   Used the "SANHANES_3.csv" dataset, which includes 42 features and 493 observations.
    -   Target variable: `1` (anemia) and `0` (no anemia).
-   **Techniques Used:**
    -   Preprocessing: Handling missing values, scaling features, and data splitting.
    -   Models: Logistic Regression, Random Forest, SVM, Naive Bayes, and XGBoost.
    -   Calibration Techniques: Platt Scaling, Isotonic Regression, and Beta Calibration.
-   **Evaluation Metrics:**
    -   Brier Score: Measures the accuracy of probability predictions.
    -   Expected Calibration Error (ECE): Assesses the calibration of predicted probabilities.
    -   Reliability Diagrams: Visual representation of model calibration.

------------------------------------------------------------------------

## **File Structure**

-   `Anemia.ipynb`: Jupyter Notebook containing the code and analysis.
-   `SANHANES_3.csv`: Dataset used for the study (not included; replace with your own if necessary).
-   `README.md`: Documentation for the repository.

------------------------------------------------------------------------

## **Key Results**

-   **Best Model:** Logistic Regression with Platt Scaling achieved the best balance between reliability and accuracy.
-   Calibration techniques significantly improved prediction reliability, especially in imbalanced data scenarios.

------------------------------------------------------------------------

## **Installation and Usage**

1.  Clone the repository:

    ``` bash
    git clone https://github.com/YourUsername/Supervised-Learning-Model-Calibration.git
    ```

2.  Navigate to the project directory:

    ``` bash
    cd Supervised-Learning-Model-Calibration
    ```

3.  Install required dependencies:

    ``` bash
    pip install -r requirements.txt
    ```

4.  Open the Jupyter Notebook:

    ``` bash
    jupyter notebook Assignment2_Supervised_Learning.ipynb
    ```

------------------------------------------------------------------------

## **Future Work**

-   Explore balancing techniques to improve model calibration further.
-   Investigate the impact of larger datasets on calibration methods.

------------------------------------------------------------------------

## **Contributing**

Feel free to open issues or submit pull requests for suggestions and improvements.

