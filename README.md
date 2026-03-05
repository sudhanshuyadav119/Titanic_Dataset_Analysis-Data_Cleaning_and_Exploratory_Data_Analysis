# Titanic_Dataset_Analysis-Data_Cleaning_and_Exploratory_Data_Analysis
<br>
# Task-02: Data Cleaning and Exploratory Data Analysis (Titanic Dataset)

## 📌 Internship

This project is completed as part of the **Prodigy Infotech Data Science Internship**.

## 📊 Objective

The objective of this task is to perform **data cleaning and exploratory data analysis (EDA)** to understand patterns and relationships in the Titanic dataset and identify factors that influenced passenger survival.

## 📁 Dataset

The dataset used in this project is the **Titanic training dataset (`train.csv`)**.

This dataset contains information about passengers aboard the Titanic and includes features such as passenger details, ticket information, and survival status.

### Dataset Features

* **PassengerId** – Unique identifier for each passenger
* **Survived** – Survival status (0 = Did not survive, 1 = Survived)
* **Pclass** – Passenger class (1st, 2nd, 3rd)
* **Name** – Passenger name
* **Sex** – Gender of the passenger
* **Age** – Age of the passenger
* **SibSp** – Number of siblings/spouses aboard
* **Parch** – Number of parents/children aboard
* **Ticket** – Ticket number
* **Fare** – Ticket fare
* **Cabin** – Cabin number
* **Embarked** – Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn

## 🔍 Steps Performed

### 1. Data Loading

The dataset (`train.csv`) was loaded into a Pandas DataFrame for analysis.

### 2. Data Exploration

Initial exploration was performed using:

* `df.head()` to view the dataset
* `df.info()` to understand column data types
* `df.describe()` to summarize numerical features

### 3. Data Cleaning

Missing values were handled to improve data quality:

* Missing values in **Age** were filled using the median.
* Missing values in **Embarked** were filled using the mode.
* The **Cabin** column was removed due to excessive missing values.

### 4. Exploratory Data Analysis (EDA)

Several visualizations were created to explore relationships between variables:

* **Survival Distribution**
* **Survival by Gender**
* **Survival by Passenger Class**
* **Age Distribution**
* **Correlation Heatmap**

These visualizations help in identifying trends and patterns affecting survival.

## 📈 Key Insights

* Female passengers had a **higher survival rate** compared to male passengers.
* Passengers in **first class had better survival chances** than those in second or third class.
* Most passengers were between **20 and 40 years of age**.
* Passenger class and gender were significant factors influencing survival.

## 🎯 Outcome

This task helped develop skills in:

* Data preprocessing and cleaning
* Exploratory data analysis
* Data visualization
* Interpreting insights from real-world datasets

## 📂 Project Files

* `Task02.ipynb` – Jupyter Notebook containing analysis and visualizations
* `train.csv` – Titanic dataset used for analysis

## 🚀 Author

**Sudhanshu Yadav**
Master’s Student in **Survey Research and Data Analytics**
