# Seaborn Library
 
I worked on the Seaborn Library's datasets called "planets" , "diamonds" , "tips" , "iris" , "flights" , "fmri" ,.

FIRST QUESTION WE WILL ASK:

What is the Story of the Data Set? In our dataset, the method is the way planets are found.
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
**BarPlot :** column chart, It is used to visualize the categorical data we have. We are using the dataset called 'diamonds'. 
- "price" in dollars (326 - 18,823)
- "carat" weight (0,2 - 5,01)
- "cut" quality ( Fair, Good, Very Good, Premium, Ideal)
- "color" color 
- "clarity" 
- "x" length in mm (0 - 10,74)
- "y" width in mm (0 - 58,9)
- "z" depth in mm (0 - 31,8)
- "depth" percentage of total depth = z/mean(x,y)
- "table" the width of the diamond in relation to its widest point


**NOTE :** In our dataset story, our ranking is listed as "fair-good-very good-premium-ideal". 

Sorting in **df.cut.head(1)** output : 'Ideal' < 'Premium' < 'Very Good' < 'Good' < 'Fair'  



**FacetGrid :** used to show dimensions added on the chart


IMPORTANT!!!!
**Our aim in ML is to try to explain the information existing in the dependent variable we aim with, by different variables.**

**Boxplot :** to visualize continuous variables. Helps in monitoring outliers. We are using the dataset called 'tips'. 
- "total_bill" The total price of the meal (including tip and VAT)
- "tip"
- "sex" gender of the person paying  (0=male, 1=female)
- "smoker" any smoker in the group (0= NO, 1=YES)
- "day" 
- "time" (0=day, 1=night)
- "size" how many person in this group



**Violin Chart :** locations in centers, a graphic boxplot-like graph in the middle, presenting the central trend


**Correlation Graphs :** expresses the relationship between variables


**Scatter Plot Matrix :**
- If there is no structural form, there is no relationship between these two variables.
- When the observation points are examined, we can say that if there are clusters at different corners, there are sub-clusters.

