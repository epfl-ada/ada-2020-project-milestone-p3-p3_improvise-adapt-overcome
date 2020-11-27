# CS- 401 Applied Data Analysis 2020
### Milestone P3: Tesco Grocery proposed extension
#### Elise Jeandupeux, Emma Bouton--Bessac and Lucas Streit


### Title
A match analysis of happiness and food consumption

### Abstract
The goal of the Tesco paper is to create a database of grocery-purchase data linked to geographic area. We are wondering if food consumption is correlated with happiness.
To examine this potential link, we decided to use the paper database along with another dataset using the same geographic area as the Tesco paper, featuring happiness. We will define a healthy diet based on the WHO definition and see if a healthy diet is correlated to better well-being or if a specific nutrient explains better happiness. Moreover, regressions will allow us to go further in our analysis, to see if certain food habits can lead to certain levels of happiness and to what extent.

### Research questions

Does a healthy food consumption lead to better well-being and happiness ? 

### Proposed datasets
We are planning to combine the paper’s dataset on Tesco food purchases and the following one : https://data.london.gov.uk/dataset/london-ward-well-being-scores
Both datasets use the same notation for London ward areas. The happiness dataset contains data from 2009 to 2013 while the Tesco data were gathered during the year 2015. However, the diabetes' dataset used in the paper is from 2013 so it should not bias our project to use the happiness dataset.

### Methods
Data wrangling : clean up the happiness dataset to be able to work with and import it correctly to the Python framework.
Data collection : Merge the two datasets (Tesco + happiness)
Establish what is a healthy diet according to the WHO and attribute a “heatlhy” score to each geographic area.
Data analysis: Perform two correlations: one between the different nutrients and entropy with the happiness score and another one between the health score and the happiness score. This will allow us to see if the happiness score depends on a healthy diet or on a specific nutrient.
We will then confirm our results by fitting different types of regression (linear, gaussian regression,...) and see if there is a correlation between the ones that have the highest correlation with happiness  and the happiness score.

### Proposed timeline
Week1: merge datasets and find characteristics of a healthy diet
Week2: compute a healthy score for each area and perform regression
Week3: interpret results and record video
### Organization within the team
Emma : Clean new dataset 
Elise: Define health score and compute it for the Tesco dataset
Lucas: Perform correlation
Elise and Emma: Perform regressions
All : Interpretation of the results
All: Prepare and record video
