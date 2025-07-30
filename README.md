# Employee Salary Prediction using Machine Learning

This project aims to predict whether an individual earns more or less than $50,000 per year based on census data. This is a classic binary classification problem in machine learning.

## 📝 Project Description

The model analyzes various personal attributes such as age, education, occupation, and hours worked per week to classify income levels. The primary goal is to build an accurate and reliable predictive model and to understand which factors are the most significant indicators of personal income.

## 💾 Dataset

This project uses the **"Adult" dataset** from the UCI Machine Learning Repository.

* **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/adult)
* **File:** `adult 3.csv`
* **Target Variable:** `income` (categorical: <=50K or >50K)

## 🛠️ Technologies Used

The project is built using Python and several key data science libraries:

* **Python 3.x**
* **Pandas:** For data manipulation and cleaning.
* **Scikit-learn:** For building machine learning models and data preprocessing.
* **Matplotlib & Seaborn:** For data visualization.
* **Jupyter Notebook:** As the development environment.

## 🚀 How to Run the Project

To run this project on your local machine, follow these steps:

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/saadiqbal09/Salary_Project.git](https://github.com/saadiqbal09/Salary_Project.git)
    ```

2.  **Navigate to the Project Directory:**
    ```bash
    cd Salary_Project
    ```

3.  **Install Required Libraries:**
    Make sure you have Python and pip installed. Then, run the following command to install the necessary libraries:
    ```bash
    pip install pandas scikit-learn matplotlib seaborn jupyterlab
    ```

4.  **Place the Dataset:**
    Ensure that the `adult 3.csv` file is in the same directory as the notebook file.

5.  **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
    This will open a tab in your browser. Click on the `.ipynb` notebook file to open it.

6.  **Run the Code:**
    Execute the cells in the notebook sequentially to see the data analysis, model training, and results.

## 📈 Results

Several machine learning models were trained and evaluated. The **Random Forest Classifier** provided the best performance for this task.

* **Best Model:** Random Forest
* **Accuracy:** Approximately **86%**

The model demonstrated a strong ability to distinguish between the two income classes, confirming that census data contains significant predictive power for this task.
