# Titanic-Data-visualisation
The data shows information about passengers, their rate of survival, factors that could have been life saving options for the passengers etc.

# Table of Content-:

- Preview
- Reason to Choose these Case study
- Pandas Methods which are used in these project
- Graph which are used
- Workdone
- Conclusion
- Result


# 1. Preview of File : https://drive.google.com/file/d/1T87lzQ7bI1-zLaYmjmS6d09NlBftoXiU/view?usp=sharing

# 2. Thoughts behind this case study : 
  - I was looking forward to review the statistics of casualty & survival chances of passengers travelling through the titanic ship that night, on a weekend after watching the titanic movie.

# 3. Pandas Methods  used :
  - .read_csv()
  - .head()
  - .info()
  - .isnull()
  - .fillna()
  - .drop(), .dropna()
  - .value_counts()
  - .sum(), .mean()
  - .describe()
  - .unique()
  - .loc()
  - .plot()
  - .DataFrame()
  - .count()
  - .append()
  - .idxmax()
  - .sort_values()
  - .groupby()
  - .get_group()
    - shape

# 4. Graphs Used :
  - Heatmap
  - Bar plot
  - Dist plot
  - Count Plot
  - Pie Chart
  - Box Plot
  
# 5. Work Done :
  - Firslt I visualised the null values of columns, and accordingly filled null values of age column with mean age and dropped cabin column which was no use to this analysis.
  - Then with dropna method I have dropped rows with the Nan values in the dataset, with isnull & sum method ensured that dataset is cleaned for analysis.
  - To start with analysis, I counted total number of passengers travelling, and actual sum of passengers with their child/sibling-passengers with count method.
  - By using value_counts I got of survived passengers & visualised it with different plots.
  - Then I visualised with countplot the affect of chosing the class of travel on their fortune of incident, turns out it did have affect on the survival rate.
  - Then I studied with countplot the rate of survival according to gender with countplot.
  - Then I plotted histogram with distplot & boxplot method for the probabiloty distribution of the age of all passengers & also those who survived the accident.
  - Also at the end I analyzed and visualized the rate of survival according to there point of embarkation.
   
  # 6.  Results :

  - According to survival record in this dataset, there were a total of **889 passengers** travelling by the titanic ship when it sank on **14 April 1912**.
  - Out of the total passengers, almost **72.5%** passengers travelling from the start of journey & only 1/3rd passengers survived the accident.
  - Most of the **unfortunate passengers** were travelling through **3rd class**, where the most **survived** passengers were travelling through **1st class**, this may tell us that *1st class might have been on the upper deck of the ship*.
  - Out of the survived passengers, count of **female is more** than that of male.
  - **50% of the passengers** are from age **20 to 35**.
  - The Titanic had the **youngest passenger** of age around *three months* as min age being **0.42 years**, where as the **eldest passenger** was of age **80 years**.
  - **68%** Survived passengers also vary in age from **15-41** yrs, according to the standard deviation & distplot.

# 7.  Conclusion :

 - If you would have been a *mid-aged* **Female** specifically in your **20-30's** travelling as a **parent/child** from a **1st class** boarded from **Cherbourg port**, you would have probably the most chances of **surviving** the Titanic-Iceberg Accident.
