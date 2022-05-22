# Week-8-Challenge--ETL-Amazing-Prime

## Overview
We have been asked to help Amazing Prim create an automated pipeline that takes in new data, perform the requested transformations, and loads the data into existing tables. In this module we refactored code on Wikipedia Movie data, Kaggle Movie Metadata, and the MovieLens rating data. Once this data is complete we are to add the processed data to our PostgreSQL database.

## Deliverables Overivew
* Deliverable #1: Write an ETL Function to Read Three Data Files
* Deliverable #2: Extract and Transform the Wikipedia Data
* Deliverable #3: Extract and Transform the Kaggle data
* Deliverable #4: Create the Movie Database 

## Deliverable Breakdwown
* Deliverable #1:

  * Creates Path
        
  ![Creates path](https://github.com/LindsayTeeters/Week-8-Challenge--ETL-Amazing-Prime/blob/main/Resources/Create%20Path_Set%20Variables%20(D1).png)
  
    * Wiki Movie Dataframe
      
  ![Wiki_DF](https://github.com/LindsayTeeters/Week-8-Challenge--ETL-Amazing-Prime/blob/main/Resources/Wiki_movies_df%20(D1).png)
  
   * Kaggle Metadata
  
   ![Kaggle DF](https://github.com/LindsayTeeters/Week-8-Challenge--ETL-Amazing-Prime/blob/main/Resources/Kaggle_meta%20(D1).png)
   
   * Ratings
  
   ![Ratings](https://github.com/LindsayTeeters/Week-8-Challenge--ETL-Amazing-Prime/blob/main/Resources/Ratings%20(D1).png)

* Deliverable #2: 

  * Filter out TV Shows
    ![Filter TV](https://github.com/LindsayTeeters/Week-8-Challenge--ETL-Amazing-Prime/blob/main/Resources/FIlter%20out%20TV%20Shows%20(D2).png)
    
  * Implement try-except bloc to catch errors while extracting
    ![try-except](https://github.com/LindsayTeeters/Week-8-Challenge--ETL-Amazing-Prime/blob/main/Resources/Try_Except%20(D2).png)
  
  * Wiki
