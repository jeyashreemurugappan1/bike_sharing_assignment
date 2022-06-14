# bike_sharing_assignment
This project aims at predicting factors on which demand of shared bike depends by building a linear regression model


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
- What is the background of your project?
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic.BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19.They want to understand the factors on which the demand for these shared bikes depends. 
Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
    Which variables are significant in predicting the demand for shared bikes.
    How well those variables describe the bike demands
- What is the business probem that your project is trying to solve?
This project is trying to predict the factors on which demand of shared bike depends 
- What is the dataset that is being used?
https://github.com/jeyashreemurugappan1/BIKE_SHARING_ASSIGNMENT/data/day.csv


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
<span style="color:brown">Demand is more on below situations. Company may want to have more bikes for matching the increase in demand</span>
<br>
<span style="color:blue"> When `temp` is good (People will prefer to travel in bike) </span>
<br>
<span style="color:blue"> With feature `year` by year (Year by Year count is increasing as company is getting famous) </span>
<br>
<span style="color:blue"> When season is winter `September 23 to dec 20`</span>
<br>
<span style="color:blue"> When season is summer `Mar 21 to june 20`</span>
<br>
<span style="color:blue"> When month is `September`. `september` month on whole has good demand</span>
<br>
<span style="color:blue"> When month is `august`. `August` month has good demand</span>
<br>
<span style="color:blue"> When day is `working day or monday`</span>
<br>
<span style="color:blue"> When date of month is D2 (`9th to 16th`) or D3 (`17th to 23rd`) </span>
<br>

<span style="color:brown">Demand is less on below sitations.Company may want to provide some offers for rental or come up with car rental options may be to address below low demand </span>
<br>
<span style="color:blue"> When `humidity` is high, when `windpeed` is high (as people may not prefer to travel in bikes)</span>
<br>
<span style="color:blue"> When day is `holiday` (obviously working people would be limited)</span>
<br>
<span style="color:blue"> When the weather is `light snow rain` (obviously people wont like to travel in bike)</span>

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Pandas - 1.3.4 
- Numpy - 1.20.3 
- Seaborn - 0.11.2
- Matplotlib - 3.4.3
- scikit-learn - 0.24.2
- statsmodels - 0.12.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project has been prepared from learning from linear regression at https://www.learn.upgrad.com


## Contact
Created by [@jeyashreemurugappan1] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
