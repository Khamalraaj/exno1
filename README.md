# Exno:1
Data Cleaning Process

# AIM
To read the given data and perform data cleaning and save the cleaned data to a file.

# Explanation
Data cleaning is the process of preparing data for analysis by removing or modifying data that is incorrect ,incompleted , irrelevant , duplicated or improperly formatted. Data cleaning is not simply about erasing data ,but rather finding a way to maximize datasets accuracy without necessarily deleting the information.

# Algorithm
STEP 1: Read the given Data

STEP 2: Get the information about the data

STEP 3: Remove the null values from the data

STEP 4: Save the Clean data to the file

STEP 5: Remove outliers using IQR

STEP 6: Use zscore of to remove outliers

# Coding and Output
import pandas as pd
import numpy as np
import seaborn as sn
df=pd.read_csv("//content//Data_set.csv")
df
![Screenshot 2024-10-18 205022](https://github.com/user-attachments/assets/086303d0-0816-40ea-a538-fd3e0ffc9                      ![Screenshot 2024-10-18 205152](https://github.com/user-attachments/assets/3488bc66-da21-4e7c-8268-9dfda60d1780)
![Screenshot 2024-10-18 205347](https://github.com/user-attachments/assets/fa2b3b97-8a3a-42ed-9544-766bb0bd428a)
![Screenshot 2024-10-18 205416](https://github.com/user-attachments/assets/2310bcfe-6ff0-4703-adfe-12a8e039caea)
![Screenshot 2024-10-18 205441](https://github.com/user-attachments/assets/dae7ce04-63e3-42bb-b617-2e48d23047ca)
![Screenshot 2024-10-18 205632](https://github.com/user-attachments/assets/b5ca40e6-95bd-4207-8157-197a0790a80d)
![Screenshot 2024-10-18 210443](https://github.com/user-attachments/assets/bef19190-b521-448d-88ce-341cc74fdda9)
![Screenshot 2024-10-18 210534](https://github.com/user-attachments/assets/bf3aaf46-ba61-4d54-9ded-20e003f9dd6f)
![Screenshot 2024-10-18 210622](https://github.com/user-attachments/assets/70d4840a-1613-4ba6-b37b-373ff82a5a96)
![Screenshot 2024-10-18 210809](https://github.com/user-attachments/assets/c0de696f-26c1-40d5-b499-a5e670dccadb)
![Screenshot 2024-10-18 210856](https://github.com/user-attachments/assets/ecaed843-38c1-4dd6-90ba-adda95fb8434)
![Screenshot 2024-10-18 215351](https://github.com/user-attachments/assets/78aa6886-a8be-40c7-b956-7c67bb08d437)
![Screenshot 2024-10-18 215414](https://github.com/user-attachments/assets/188559b2-8e0d-4190-bd92-db2f0a2ef785)
![Screenshot 2024-10-18 215507](https://github.com/user-attachments/assets/22b23527-1e95-46c5-a31c-725bc2ba77b7)
![Screenshot 2024-10-18 215729](https://github.com/user-attachments/assets/5c8319b6-6952-4038-bfd4-8cd89c6f9748)
![Screenshot 2024-10-18 215740](https://github.com/user-attachments/assets/91ce1e2a-53de-4dce-8ad5-b3e0cfd66435)
![Screenshot 2024-10-18 220648](https://github.com/user-attachments/assets/7a91ee9e-c605-4ea2-8548-f3bf7be69f48)






# Result
     Thus we have cleaned the data and removed the outliers 
