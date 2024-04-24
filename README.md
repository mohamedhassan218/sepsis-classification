# Sepsis Classification

This repository contains a Jupyter Notebook contains the implementation and comparison of nine different classification algorithms on the sepsis dataset. The notebook demonstrates the performance of each algorithm and provides insights into their strengths and weaknesses. 

The algorithms included are:

1. Logistic Regression
2. Decision Trees
3. Random Forest
4. Support Vector Machines (SVM)
5. K-Nearest Neighbors (KNN)
6. Naive Bayes
7. Gradient Boosting
8. AdaBoost
9. XGBoost

## Dataset
The classification task is performed on the [sepsis dataset](https://www.kaggle.com/code/anhhunhvn/detect-sepsis-with-patients-dataset), which consists of some characteristics about the paitient and a flog if he has sepsis or not.

## How to Use
Simply open the Jupyter Notebook `sepsis_classification.ipynb` to explore the implementations and results. Each algorithm is thoroughly explained, along with code snippets and visualizations for better understanding.

## Requirements
- Python
- Jupyter Notebook or you can use Colab (but you'll need to change the path of the datasets)
- Libraries: NumPy, pandas, scikit-learn, matplotlib, seaborn

## Usage
1. Clone this repository.
   
   ```
   git clone git@github.com:mohamedhassan218/sepsis-classification.git
   ```

2. Install the required dependencies.

    ```
    pip install -r requirements.txt
    ```

3. Open the Jupyter Notebook and run the cells sequentially to reproduce the analysis.

## Contributions
I welcome contributions from anyone. If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request and feel free to take the code, customize it and try different ideas.

## Reference
I've used this [article](https://medium.com/@rasmowanyama/sepsis-classification-machine-learning-project-with-fastapi-deployment-how-data-science-saves-b3d0f0b98316) as the base to the code in addition to changing and adding some snippets so thanks to the author.