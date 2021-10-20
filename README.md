# RainPrediction


## Overview 

### The purpose of this project is to analyze and visualize the behavior of the weather in Australia. To get to knows if it will rain or not the next day.
### Moreover, the benefits of the system are to help any person decide whether he wants to go out and have some outside activities or not because it may rain tomorrow.

### The dataset contains about 10 years of daily weather observations from many locations across Australia.
### RainTomorrow is the target variable to predict. It will be raining the next day, Yes or No? This column is Yes if the rain for that day was 1mm or more.


## Cleaning

### In The beginning, I started with 22 Features with missing values, I deleted all the features with a missing value above 15%.
### After that, I filled the missing values of numerical features using mean and categorical features using the mode, and I ended with 18 features.


## Data Exploration

### In this scatter, we can see the name of the cities and how many times the rainfall.

<img width="1106" alt="Screen Shot 2021-10-21 at 1 42 04 AM" src="https://user-images.githubusercontent.com/58388925/138183192-4f80fa33-513a-4289-b24c-aa013ac7ca26.png">

### Here in the boxplot, I am looking for linearly separated features.

<img width="391" alt="Screen Shot 2021-10-21 at 1 57 55 AM" src="https://user-images.githubusercontent.com/58388925/138185354-6a3a45cf-35a2-44c2-b56d-5dcfb1e17900.png"> &nbsp; &nbsp; &nbsp; &nbsp; <img width="391" alt="Screen Shot 2021-10-21 at 1 58 17 AM" src="https://user-images.githubusercontent.com/58388925/138185365-2cc233ab-ac12-44c0-beaf-71c5eede9eec.png">
### In these two boxplots, not much impact of min or max temperature is on rain tomorrow
#### ___________________________________________

<img width="391" alt="Screen Shot 2021-10-21 at 1 58 32 AM" src="https://user-images.githubusercontent.com/58388925/138185741-60402173-ad15-430e-bd7d-6c1677683792.png"> &nbsp; &nbsp; &nbsp; &nbsp; <img width="391" alt="Screen Shot 2021-10-21 at 1 58 36 AM" src="https://user-images.githubusercontent.com/58388925/138185746-c83fca43-c520-4223-a695-eac72e6e7a9b.png">
### On the other hand humidity at 9 am, and 3 pm in the range of 55-90 can cause rain the next day.

### The heat map

<img width="869" alt="Screen Shot 2021-10-21 at 2 27 05 AM" src="https://user-images.githubusercontent.com/58388925/138186390-6759c95e-8daa-4fc8-bb27-16b96dd659fa.png">

### Sine the Teamp9am and Temp3pm have a high correlation with MaxTemp and MinTemp so we will remove them.

## Modelling





