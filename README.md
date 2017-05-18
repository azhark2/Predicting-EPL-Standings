# Scikit-learn-Project  

`Data_IO.ipynb`: converts the SQL data from the [Kaggle](https://www.kaggle.com/hugomathien/soccer) competition into separate .csv files  
`Team_Attributes.ipynb`: encodes categorial data from *Team_Attributes.csv* into numerical values; saves data as *Team_Attributes_processed_ordinal.csv*  
`Team_Attributes_Separation.ipynb`: divides *Team_Attributes_processed_ordinal.csv* into five datasets according to year   
`premier_league_scores.ipynb`: uses web-scraping to obtain team scores for various seasons.
`season_points_scraping.ipynb`: uses web-scraping to obtain team scores for various seasons.  
`Machine_Learning_Preparation.ipynb`: takes the data from each year and combines it with the associated team name and team points; also standardizes the data (z-score normalization) - outputs are in *Standardized Data* section.      
`Machine_Learning_Preparation-raw_data.ipynb`: takes the data from each year and combines it with the associated team name and team points. Does not standardize data - outputs are in *Raw Data* section.   
`Data_Exploration.ipynb`: Visualizes the data in the *Raw Data* section.  
`LinearRegression.ipynb`: Performs linear regression on data   
`SVM.ipynb`: Jupyter notebook showing the support vector machine (SVM) regression method   
  
</br>  
## Data (prepared for machine learning):  
---  
*Raw Data*  
team_attributes_processed-2009-2010-raw_data.csv  
team_attributes_processed-2010-2011-raw_data.csv  
team_attributes_processed-2011-2012-raw_data.csv  
team_attributes_processed-2013-2014-raw_data.csv  
team_attributes_processed-2014-2015-raw_data.csv  
team_attributes_processed-2015-2016-raw_data.csv  
</br>  
*Standardized Data (Z-score):*    
team_attributes_processed-2009-2010.csv  
team_attributes_processed-2010-2011.csv  
team_attributes_processed-2011-2012.csv  
team_attributes_processed-2013-2014.csv  
team_attributes_processed-2014-2015.csv  
team_attributes_processed-2015-2016.csv  
