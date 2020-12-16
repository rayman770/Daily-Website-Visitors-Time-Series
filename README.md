# Daily-Website-Visitors-Time-Series
![website traffic](https://websitechecker.com/wp-content/uploads/2020/04/AdobeStock_154964316-1024x576.jpeg)

- **Dataset Source**
    - https://www.kaggle.com/bobnau/daily-website-visitors


- **Context of Dataset**
    - This file contains 5 years of daily time series data for several measures of traffic on a statistical forecasting teaching notes website whose alias is statforecasting.com. 
    
    
- **Background Information**
    - There are 2,167 rows of data spanning the date range from September 14, 2014 to August 19, 2020.
    - A visit is defined as a stream of hits on one or more pages on the site on a given day by the same user, as identified by IP address. 
    - Multiple individuals with a shared IP address (e.g., in a computer lab) are considered as a single user, so real users may be undercounted to some extent.
    - The data was collected through a traffic monitoring service known as StatCounter.    
    

- **Attribute Information**
    - Row: Number of rows starting from 0
    - Day: Day of the week (Monday through Sunday)
    - Day.Of.Week: Numeric form of Day (Sunday = 1, Monday = 2, ... , Friday = 6, Saturday = 7)
    - Date: Date of website visits
    - Page.Loads: Number of webpages loaded for visit
    - Unique.Visits: A visit is classified as "unique" if a hit from the same IP address has not come within the last 6 hours. The count of unique visitors is the sum of the counts of returning and first-time visitors by definition.
    - First.Time.Visits: Number of visitors that are not identified by cookies
    - Returning.Visits: Returning visitors are identified by cookies if those are accepted.
    
 
- **Content**
    - Preparing Dataset
        - Importing Dataset
        - Preprocessing
        
    - Analyzing Data
        - Summaries of Categorical and Numeric Data
        - Pair Plot of Daily Website Visit
        - Plot by Period - Daily Totals
        - Plot by Period - Monthly Totals
        - Plot by Period - Yearly Totals
        - Plot by Period - Weekdays
        - Decomposition into Trend and Seasonality
        - Forecasting with Facebook Prophet
