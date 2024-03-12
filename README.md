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

# Coding
  import pandas as pd
df=pd.read_csv("/content/Data_set.csv")

df.head(5)

df.tail(3)

df.info()

df.describe()

df.isnull()

df.notnull()

df.dropna(axis=1)

dfs=df[df['rating']>8]
dfs

df.iloc[[1,3,6],[1,4]]

df=df.fillna(0)
df      

OUTPUT:

![1](https://github.com/maha712/exno1/assets/121156360/42bd4a2a-8090-4c47-b422-db097a3c4299)

![2](https://github.com/maha712/exno1/assets/121156360/81e64164-561f-46c3-94cf-ca9f1c82f0cb)

![3](https://github.com/maha712/exno1/assets/121156360/d37f3f78-cd0b-4175-bb4e-3d254d4a8997)

![4](https://github.com/maha712/exno1/assets/121156360/8af4fce8-1718-4df0-970a-e68ce39ecb51)

![5](https://github.com/maha712/exno1/assets/121156360/b5cc361b-db32-4700-be4e-7cb00410e22d)

![6](https://github.com/maha712/exno1/assets/121156360/78594c88-48b5-4e13-8ffa-a0ca1ae33e0b)

![7](https://github.com/maha712/exno1/assets/121156360/ffaa11f5-5103-4a32-98b3-f5b3ad04e6c9)

![8](https://github.com/maha712/exno1/assets/121156360/4f8fa7cc-5d20-4f8a-b069-db0b6f1ad2f6)

![9](https://github.com/maha712/exno1/assets/121156360/fb994fc9-8cd5-4587-a5d2-558e46555a84)



![10](https://github.com/maha712/exno1/assets/121156360/96ff5b41-b335-4368-a5ea-9586ccfda075)





# Result
      Thus the given data is read,cleansed and the cleaned data is saved into the file.
