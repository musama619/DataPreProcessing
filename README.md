# DataPreProcessing

## 1. Handling Missing Values

 ## 2. Extended Data Dictionary (EDD)
![image](https://user-images.githubusercontent.com/34093998/87990828-381ab600-cafe-11ea-82e4-1641c32377aa.png)


 ## 3. Outliers 
 #### Reason
    * Data Entry Error
    * Sampling Error
    * Measurement Error
Detect Outliers using EDD and visualizations using scatterplot, histogram, boxplot or jointplot

## 4. Outliers Treatment
1. Capping and Flooring
   Impute values above P99*3 and below 0.3*P1
2. Other Methods
    
## 5. Transform Skewed Data
    * Log Function 
      helpful_log = np.log(df.Helpful_Votes + 1)

## 6. Transform and Remove Irrevelant Variables
 
