# Seaborn Library
 
I worked on the Seaborn Library's datasets called "planets" , "diamonds".

FIRST QUESTION WE WILL ASK:

What is the Story of the Data Set? In our dataset, the method is the way galaxies are found.
- "number" refers to the number of planets in the system.
- "orbital_period" refers to the orbital period.
- "mass" means mass.
- "distance" refers to distance.
- "year" found date.

**Missing Values**  
We have different two ways :

- We can call all missing values ​​in the array as zero : **df["value_name"].fillna(0, inplace=True)**
- Or we can assign the mean value into the array : **df["value_name"].fillna(df.value_name.mean(), inplace=True)**

**DATASET STORY**

**Scatter Charts :**
- **BarPlot :** column chart, It is used to visualize the categorical data we have. We are using the dataset called 'diamonds'. 
     
