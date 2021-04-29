# Capstone Project
David Cuervo

### Objective
Explore the relationship between industrial toxic releases and the socioeconomic demographics of the neighborhoods they are in.

Do poorer neighborhoods or predominantly minority neighborhoods have more pounds of toxic releases compared to wealthier, white neighborhoods?

### Repository Contents
- Raw Data folder
- Cleaned Data folder
- EDA notebook
- Modeling notebook
- Presentation slides

### Exploratory Data Analysis
<img width="711" alt="Screen Shot 2021-04-20 at 12 59 45 PM" src="https://user-images.githubusercontent.com/57383419/115976222-62881c80-a531-11eb-8be3-b79304b45f31.png">

Identified top 10 most polluted counties
![counties_texas](https://user-images.githubusercontent.com/57383419/115976215-3f5d6d00-a531-11eb-8ad0-c3dee6c7b567.png)

Top polluters in Texas
![companies_texas](https://user-images.githubusercontent.com/57383419/115976225-6c118480-a531-11eb-87cf-099c5b48b066.png)

Top 10 Chemicals Released
![chemicals_texas](https://user-images.githubusercontent.com/57383419/115976231-79c70a00-a531-11eb-92a5-705e64b67b53.png)

### Results
- Built linear and logistic regression, decision tree, and random forest models 
- Most accurate was the random forest: 45.22%

![feature_importance_revised](https://user-images.githubusercontent.com/57383419/116602572-85c81880-a8f1-11eb-8d31-8a0d34da0575.png)

Top 4 Features 

![American_Indian_bargraph](https://user-images.githubusercontent.com/57383419/116602635-98dae880-a8f1-11eb-88be-69079cd03499.png)

![Population_boxplot](https://user-images.githubusercontent.com/57383419/116602646-9d070600-a8f1-11eb-95a6-98d19e5c951e.png)

![Asian_bargraph](https://user-images.githubusercontent.com/57383419/116602652-9f696000-a8f1-11eb-86d7-123950133caa.png)

![Population_125_PL_boxplot](https://user-images.githubusercontent.com/57383419/116602680-aa23f500-a8f1-11eb-8ba9-f72684d7f3ac.png)


### Conclusions
- Some relation between poverty and toxins released
- The higher the Asian population, the less toxins releases in that ZIP code
- American Indians only make up 1% of the Texan population
- Future studies could explore:
  - More states, not just Texas
  - The number of actual industries in a neighborhood, not the pounds of toxins released
  - Other sources of pollution such as: bus depots, water treatment facilities, municipal waste sites
