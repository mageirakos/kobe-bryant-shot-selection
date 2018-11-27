# Kobe-Bryant-Shot-Selection
The data is taken from kaggle's Kobe Bryant Shot Selection competition : https://www.kaggle.com/c/kobe-bryant-shot-selection  

## Helpfull kaggle kernels
I would like to credit the following kernels that helped me alot with my analysis:
⋅⋅*  https://www.kaggle.com/khozzy/kobe-bryant-shot-selection/kobe-shots-show-me-your-best-model
⋅⋅*  https://www.kaggle.com/selfishgene/kobe-bryant-shot-selection/psychology-of-a-professional-athlete  
⋅⋅*  https://www.kaggle.com/apapiu/kobe-bryant-shot-selection/exploring-kobe-s-shots

## About
Kobe Bryant marked his retirement from the NBA by scoring 60 points in his final game as a Los Angeles Laker on Wednesday, April 12,    2016. Drafted into the NBA at the age of 17, Kobe earned the sport’s highest accolades throughout his long career.  
  
Using 20 years of data on Kobe's swishes and misses, can you predict which shots will find the bottom of the net? This competition is well suited for practicing classification basics, feature engineering, and time series analysis. Practice got Kobe an eight-figure  contract and 5 championship rings. What will it get you?  
  
This data contains the location and circumstances of every field goal attempted by Kobe Bryant took during his 20-year career.The task is to predict whether the basket went in (shot_made_flag).  

To avoid leakage, your method should only train on events that occurred prior to the shot for which you are predicting!     
    
The field names are self explanatory and contain the following attributes:    
   
action_type  
combined_shot_type  
game_event_id  
game_id  
lat   
loc_x  
loc_y  
lon   
minutes_remaining  
period  
playoffs  
season   
seconds_remaining  
shot_distance  
shot_made_flag (this is what I want to predict)  
shot_type  
shot_zone_area  
shot_zone_basic  
shot_zone_range  
team_id  
team_name  
game_date  
matchup  
opponent  
shot_id  
   
## Version 0.1
-Data Preprocessing   
-Creating some new features  
-Exploratory Data Analysis answering the questions:  
    1)What is Kobe's FG% and how many shots did he take?  
    2)Can we plot Kobe's shot attempts and accuracy as the game progresses?  
    3)Can we visualize based on location if distance from the basket, court zone, shot type etc. makes a difference in shot accuracy?   
    4)Can we plot out Kobe's accuracy based on the different features in our dataset?  
  
## To be done
1) Better visualizations  
2) Answer more questions  
3) Train models that avoid "leakage"  
