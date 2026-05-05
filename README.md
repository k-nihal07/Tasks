# Tasks
Task 01: Data Cleaning and Preprocessing to build a strong foundation.
Data cleaning is often called the "janitorial" work of data science, and this task focuses on making raw, "messy" data usable for analysis.

📊 About the Dataset

I used the BigMart Sales dataset, which I downloaded from Kaggle. Specifically, I worked with the Test.csv file, which is roughly 527 KB and contains 11 columns of data.

🧹 What I Did

My goal was to build a pipeline to fix the broken parts of this dataset. Here is how I cleaned it:


Handled Missing Values: I used mean and mode imputation to fill in empty cells. For example, the Item_Weight and Outlet_Size columns had many missing entries that needed fixing.


Standardized Categories: I corrected inconsistent categorical data. In the Item_Fat_Content column, there were different labels meaning the same thing (like "LF", "low fat", and "Low Fat"), which I standardized into a uniform format.

🛠️ Tools Used

Language: Python 

Libraries: Pandas 

Environment: Jupyter Notebook 

📁 Files in this Repository

Task1_datacleaning.ipynb: My main Jupyter Notebook file containing all the Python code and step-by-step explanations.

cleaned_test_data.csv: The final, polished dataset I produced at the end of the script.

requirements.txt: A simple text file listing the libraries used for this project.
