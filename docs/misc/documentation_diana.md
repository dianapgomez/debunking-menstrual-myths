## 1. Dataset Menstrual cycle data with factors
Info: This dataset contains synthetic menstrual cycle data for 100 users. It is designed to facilitate research and analysis of factors influencing menstrual health and to enable the development of predictive models for estimating the start date of the next menstrual cycle. The dataset includes a variety of features such as demographic information, lifestyle factors, and menstrual cycle details.

[Fuente](https://www.kaggle.com/datasets/akshayas02/menstrual-cycle-data-with-factors-dataset) 

### Exploratory data analysis

Column Name Description
- `User ID`: Unique identifier for each user.
- `Age`: Age of the user (in years).
- `BMI`: Body Mass Index of the user.
- `Stress Level`: Self-reported stress level (scale: 1-5, where 1 = low, 5 = high).
- `Exercise Frequency`: Frequency of exercise (options: Low, Moderate, High).
- `Sleep Hours`: Average hours of sleep per night.
- `Diet`: Dietary habits (options: Balanced, Vegetarian, High Sugar, Low Carb).
- `Cycle Start Date`: Start date of the menstrual cycle.
- `Cycle Length`: Length of the menstrual cycle (in days).
- `Period Length`: Duration of the period (in days).
- `Next Cycle Start`: Date Start date of the next menstrual cycle (target variable for prediction).
- `Symptoms`: Common menstrual symptoms (options: Cramps, Mood Swings, Fatigue, Headache, Bloating).


### 1. Data type:

RangeIndex: 895 entries, 0 to 894
Data columns (total 12 columns):
 #   Column                 Non-Null Count  Dtype  
---  ------                 --------------  -----  
 0   User ID                895 non-null    int64  
 1   Age                    895 non-null    int64  
 2   BMI                    895 non-null    float64
 3   Stress Level           895 non-null    int64  
 4   Exercise Frequency     895 non-null    object 
 5   Sleep Hours            895 non-null    float64
 6   Diet                   895 non-null    object 
 7   Cycle Start Date       895 non-null    object 
 8   Cycle Length           895 non-null    int64  
 9   Period Length          895 non-null    int64  
 10  Next Cycle Start Date  895 non-null    object 
 11  Symptoms               895 non-null    object 
dtypes: float64(2), int64(5), object(5)


### 2.  Identifying null values:

There are no missing values.

### 3.  Identifying duplicates:
There are no duplicates.