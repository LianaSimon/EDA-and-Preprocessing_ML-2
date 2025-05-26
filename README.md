# EDA and Preprocessing for Machine Learning


## Project Objective

### The primary objective of this project is to design and implement a robust data preprocessing system that effectively addresses common data quality challenges, including missing values, outliers, inconsistent formatting, and noise. By performing thorough data exploration, cleaning, and transformation, this project aims to enhance the quality, reliability, and overall usefulness of the data, making it suitable for subsequent machine learning model development.


## Dataset

### The dataset used for this project is the Employee.csv file you provided.

#### *File Name: Employee.csv

#### *Source: User-provided CSV file.

#### (Please ensure the Employee.csv file is placed in the same directory as the Python script.)

#### This project is tailored to process the specific structure and content of the Employee.csv dataset.



## Key Components

### This project covers the following essential stages of data preprocessing:

### 1. Data Exploration 

#### Objective: To gain initial insights into the dataset's structure, content, and statistical properties.

#### Tasks Performed:

* Loading the Employee.csv dataset and displaying its initial information (.info(), .head()).

* Listing unique values and their counts for each feature to understand data diversity and potential inconsistencies.

* Performing comprehensive statistical analysis (.describe()) on numerical features to identify distributions, central tendencies, and spread.

* Demonstrating column renaming for better readability and consistency (specifically 'Age' to 'Years_Old' and 'Salary' to 'Monthly_Salary').


### 2. Data Cleaning 

#### Objective: To identify and rectify data quality issues that can negatively impact machine learning model performance.

#### Tasks Performed:

* Identifying and quantifying missing values across all features.

* Replacing specific inappropriate values (e.g., 0 in the 'Age' column) with NaN to treat them as missing data.

* Removing all duplicate rows to ensure data uniqueness.

* Detecting outliers in numerical features using the Interquartile Range (IQR) method.

* Treating null values in all columns: numerical columns are imputed with their median, and categorical columns are imputed with their mode (most frequent value).


### 3. Data Analysis 

#### Objective: To derive meaningful insights from the data through filtering and visualization.

#### Tasks Performed:

* Filtering the dataset based on specific conditions (e.g., Years_Old > 40 and Monthly_Salary < 5000) to analyze subsets of data.

* Creating a scatter plot to visualize the relationship between 'Years_Old' and 'Monthly_Salary'.

* Counting the number of individuals from each 'Place' and representing this distribution visually using a bar chart.


### 4. Data Encoding 

#### Objective: To transform categorical variables into numerical representations, making them compatible with machine learning algorithms.

#### Tasks Performed:

* Label Encoding: Converting categorical labels into numerical values. This is applied to suitable categorical columns in Employee.csv.

* One-Hot Encoding: Creating new binary columns for each category. This is applied to nominal categorical columns like 'Company', 'Place', and 'Country' in Employee.csv.


### 5. Feature Scaling

#### Objective: To normalize the range of independent variables or features, ensuring that no single feature dominates the learning process due to its scale.

#### Tasks Performed:

* StandardScaler (Z-score normalization): Transforms data to have a mean of 0 and a standard deviation of 1.

* MinMaxScaler: Scales and transforms data so that it fits within a specific range (e.g., 0 to 1).

  

### How to Run the Code

* Save the Code: Save the provided Python code as a .py file (e.g., eda_project.py).

* Place Dataset: Ensure your dataset (Employee.csv) is in the same directory as the Python script.

* Install Dependencies: Open your terminal or command prompt and navigate to the directory where you saved the file. Install the necessary Python libraries using pip:

* pip install pandas numpy matplotlib seaborn scikit-learn

* Run the Script: Execute the Python script from your terminal:python eda_project.py

* The script will print various outputs to the console, showing the results of each preprocessing step. It will also display generated plots for data analysis.


  ## Peep into Jupyter Notebook

  ### 1. Importing libraries,loading dataset and displaying head.

  ![image](https://github.com/user-attachments/assets/fae5e58b-08f5-4b53-b2cf-e82ed8d85aad)


  ### 2. Data Exploration.

  ![image](https://github.com/user-attachments/assets/20c35951-84f9-41dd-a098-ce5825f04440)

  ![image](https://github.com/user-attachments/assets/c886a120-9048-4ad8-98d9-db40c861e1a4)

  ![image](https://github.com/user-attachments/assets/ffb04c09-e2bb-41ee-839c-197dae328ca1)

  ![image](https://github.com/user-attachments/assets/a0b70b48-b237-442c-8177-14af0a3b7964)



 ### 3. Data Cleaning 

 ![image](https://github.com/user-attachments/assets/b386c786-4a12-417a-bf96-a5c2c53c9b27)

 ![image](https://github.com/user-attachments/assets/53a824ef-45e8-4ab8-9e15-5550b96b3d3e)

 ![image](https://github.com/user-attachments/assets/14d6790f-8358-4af9-9caf-3aafa7d12202)

 ![image](https://github.com/user-attachments/assets/177abbe8-38d8-4dab-918a-e15d3b27511b)

 ![image](https://github.com/user-attachments/assets/ecac731d-39fd-4b77-a7bb-c2984005678f)

 ![image](https://github.com/user-attachments/assets/f807bb1c-5e8e-4420-9aba-60b75c8e48d3)

 ![image](https://github.com/user-attachments/assets/1d93a4e6-07f7-428b-ac53-fbd9be5b9d75)


 ### 4. Data Analysis 

 ![image](https://github.com/user-attachments/assets/47476576-790e-4c87-b107-00431ec92686)

 ![image](https://github.com/user-attachments/assets/84d99b89-632a-445c-a0ca-ef8287338e3b)


### 5. Data Encoding



 










 
