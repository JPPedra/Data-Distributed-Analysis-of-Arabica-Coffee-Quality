# CS5811 - Data Distributed Analysis 

Reference:https://github.com/jldbc/coffee-quality-database
This GitHub Repository contains the group work performed for the Data Distributed Analysis. 

This project shows data analysis performed on Arabica Coffee Beans dataset, which was obtained from https://www.kaggle.com/datasets/ankurchavda/coffee-beans-reviews-by-coffee-quality-institute. This dataset is from the *'Coffee Quality Institute'*.

The current dataset, `ArabicaCoffeeBeans.csv`, which can be found in the Data folder, contains 1319 observations and 44 attributes. The `Data Analysis-Coffee.Rmd` files shows the data analysised performed on this data set, including data cleaning, preparation and exploratory data analysis (EDA), to aid each of us to perform different predictive machine learning techinque to answer the following research questions: "Given the attributes of this dataset, can we predict the overall coffee quality score?"

# The Metadata

## Coffee Sample Information:
- Country.of.Origin
- Farm.Name
- Lot.Number
- Mill
- ICO Number 
- Company
- Altitude 
- altitude_low_meters
- altitude_high_meters
- altitude_mean_meters
- unit_of_measurement
- Region
- Producer
- Number.of.Bags
- Bag Weight
- In.Country.Partner
- Harvest.Year
- Grading.Date
- Owner
- Owner.1
- Variety
- Processing.Method

## Cupping Scores
- Aroma
- Flavor
- Aftertaste
- Acidity
- Body
- Balance
- Uniformity
- Clean.Cup
- Sweetness
- Cupper.Point 
- Total.Cup.Points

## Green Analysis
- Moisture
- Category.One.Defects 
- Category.Two.Defects
- Quakers
- Color
- Species

## Certification Information
- Expiration
- Certification.Body
- Certification.Address
- Certification.Contact

## Subsetted Dataset for Exploratory Data Analysis:
From the Data Cleaning and Preparation, the dataset has been subsetted and the following attributes are used for exploratory data analysis:
  
- Country.of.Origin       
- Number.of.Bags               
- Bag.Weight                                   
- Processing.Method                             
- Aroma                                         
- Flavor                                        
- Aftertaste                                    
- Acidity                                       
- Body                                          
- Balance                                       
- Uniformity                                    
- Clean.Cup                                     
- Sweetness                                     
- Cupper.Points                                 
- Total.Cup.Points                              
- Moisture                                      
- Category.One.Defects                          
- Quakers                                       
- Category.Two.Defects
