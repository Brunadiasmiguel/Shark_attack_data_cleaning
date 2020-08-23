![IronHack Logo](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_d5c5793015fec3be28a63c4fa3dd4d55.png)

# Shark_attack_data_cleaning

## Project description

The goal of the project is to clean a dataset about Shark attacks. I´ve assumed that I was told to follow a few requests throughout the data cleaning, specifically to focus on the last 20 years and to research the most well known shark species and focus my analysis on them. The main focus of the project is to show seasonality, demographics and geographics of the attacks and the type of attacks and to analyse if the attacks come mostly from provokation or not since I was hypothetically hired by a company focus on shark conservation.



## Questions & Hypotheses

I assumed I worked for a company focus on relating the attacks with seasonality, demographics and geographics as mentioned beforehand. Therefore, those were the main focus on my analysis. I assumed one goal would be to show empirically that sharks can be influenced by provokation or not, to help shark protection ideally - which I assumed priori a lot of attacks would come by provokation. I considered seasonality important (since global warming can be related with shark attacks according to some studies), geographics (to give some insights about areas that can be dangerous anyways) and demographics (to understand "who" got injuried or died from shark attacks).

## Dataset

The dataset was collected on Kaggle.com and it is in the repository as sharkoriginal.csv. The data had some irrelevant information for my analysis and needed to be restructured for further analysis about shark attacks.

## Database

The database consists in one single table. The final table has 15 columns and 646 rows.

## Workflow

The workflow started with checking the row data. Secondly, selecting what data is unnecessary looking empiracally at it. Then, checking the data once again to spot unnecessary data for the goal of the analysis. Focusing on the analysis goals and requirements, I applied some concepts and cleaned up the data (mostly categorical) in order to ease the clustering and posterior analysis. I´ve also deleted a considerable amount of data, mostly to improve my data cleaning skills, and supported it by initial hypotheses of date and species restrictions. 

## Organization

The dataset given was mostly categorical. Therefore, the core of the analysis was to drop unnecessary information and make the information filtered readable to any user and posterior analysis.
Firstly, I deleted the irrelevant information. Then, checked column by column what could be improved as the jupyter notebook file shows. I created a draft list with improvements to be applied to each column.
The repository contains the jupyter file with the code named data-wrangling.ipynb , the messy dataset as sharkorigival.csv and the clean data csv as csharks.csv.

## Links

Link to repository: https://github.com/Brunadiasmiguel/Shark_attack_data_cleaning.git