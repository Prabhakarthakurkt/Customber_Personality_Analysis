# Customber_Personality_Analysis
Customber Personality Analysis is a detailed analysis of a company's idea custobers. it helps a business to better understand it is coustombers
and makes it easier for them to modify products according to the specific needs, behaviors and concerns of different types of coustombers.

customber personality analysis helps a business to modifiy its product based on its target customers from different types of customber segments.
for example, instead of spending money to market a new product to every customber in the company's database, a company can analyze which customber segment is  most likely to buy the product and then 
product and then market the product only on that particular segment.

# Time Line of the project:

  . Importing libraries
  . Data Analysis
  . Data Cleaning and Feature Engineering 
  . performing Clustering 


# Importing Libraries

      import pandas as pd ##analysis
      import numpy as np ### comptutational ability
      import seaborn as sns
      import matplotlib.pyplot as plt  ###visualization
      %matplotlib inline


      df = pd.read_csv("marketing_campaign.csv",sep='\t')

      df

      df.shape

      df.info()


      df.dtypes

# Data Analysis

     null Values

     df.isnull()


    mean=df['income'].main()
    df['income'=df['income'].fillna(mean)

let us create a new column by using year of birth


     df['Age']=2022-df['Year__Birth']
     df['age']


     sns.distplot(df['Age'],color='red')

   

