# Group-project-2
# Mist 4610 Group Project 2
## GROUP 1: NYPD Arrests Dataset

## Team Name: 
4610Fa24Group1

## Team Members:

1. Bond Surber [@bondsurber](https://www.github.com/bondsurber)
2. Sidd Kawatra [@siddKawatra](https://github.com/siddKawatra)
3. Louis Miranda [@louismiranda](https://github.com/louismiranda)

## Description of dataset:

Our dataset is a historical record of all the New York Police Department's (NYPD) arrests made from 2006-2023. We obtained our dataset through this website given to us by Dr. Srinivasan: [https://catalog.data.gov/dataset]. Our dataset is composed of 19 columns consisting of more than 5 million rows of data (approx. 5,725,522 rows) that vary in terms of data types. It details the type of offense committed (Dangerous Drugs, Assault,...), the level of the offense committed (Felony, Misdemeanor,...), the borough of the arrest (Brooklyn, Manhattan,...), and the perpetrator's age group (<18, 18-24,...) and gender (M, F, U) which are all of data type 'String'. It also details the date of the arrest, including the month, day, and year, which is of data type 'Date & Time'. Additionally, the arrest key is recorded which is of data type 'Number(Whole)' and the location of the arrest is listed in terms of longitude and latitude which are both of data type 'Number(Decimal)'. A screenshot of our dataset in .xls format can be seen below, in which the columns highlighted in gold are the dimensions used in our project. Overall, this dataset has a variation of different dimensions that help us dive deeper into the arrests and crimes that occurred in New York City (NYC). 


<img width="1440" alt="Screenshot 2024-11-25 at 12 28 53 PM" src="https://github.com/user-attachments/assets/829a2a45-d649-4e31-ad6c-58bcdac70eb8">


## Question 1:

Question: Which demographic factors, specifically age or gender, are most strongly associated with certain types of offenses?

Importance: 

This question is important because it allows one to understand how demographics come into play when NYPD are making arrests, and allow one to identify the relationships between age, gender, and type of offense committed, as well as explore the patterns associated with their relationships. This allows one to answer questions like "Are younger individuals more involved in specific types of offenses, like theft, compared to older groups?", which can pinpoint which age groups and gender are most high-risk for theft or other types of offenses. Furthermore, this question can reveal underlying systemic behavioral problems that tend to develop during earlier ages and continue to develop as they get older, which could be the root cause for some of the broader crime challenges that New York City faces. By answering this question, everyone in the New York City community, from the NYPD and policymakers to the people, can collaborate together to build targeted intervention programs that can prevent a certain demographic group from committing the crime they're most associated with in the first place, or stop them from repeating the offense again as they grow older. Additionally, this question helps to build trust between the people and the police by providing better transparency in what types of people are being arrested, ensuring any potential bias or inequalities in arrests is openly identified and addressed.  


<img width="1440" alt="Screenshot 2024-11-25 at 2 53 06 PM" src="https://github.com/user-attachments/assets/153b3396-4667-4d9a-84a8-c37da31df7cb">
<img width="438" alt="Screenshot 2024-11-25 at 3 40 40 PM" src="https://github.com/user-attachments/assets/922d6802-0347-4a27-85b1-3ff2b006d8a8">


In this visualization, we created a heatmap to illustrate the percentage of arrests that make up a certain type of offense based on age group and gender; in other words, how likely are arrests for a specific crime to be made up by a certain age group and gender. We were able to identify that Males in the 25-44 age group were consistently the majority of arrests across all types of offenses, showing that this demographic group is the most high-risk overall. Furthermore, out of the total number of arrests for the offense "Cannabis Related Offenses", 28.29% were Males ages 18-24 and 51.07% were Males ages 25-44, marking almost a 2x jump in between the demographic groups; this is also the same case for arrests of "Dangerous Drugs" where Males in 18-24 made up 24.53% and jumped significantly to 38.34% for Males in 25-44. This shows that NYC Males who are arrested for cannabis and other drugs at an early age are more than likely to repeat the same offense again when they are older, revealing that drug-related habits that exhibit in early ages tend to continue and attribute to drug-related offenses later down the line. This information can be a huge benefit to NYPD as they can build more drug awareness campaigns to prevent the early onset of drug addiction among the youth and create substance-abuse rehabilitation programs or drug courts to focus more on helping older people get clean and recover from their addiction, instead of incarcertions. We continued to analyze this same data in our next visualization.


<img width="1440" alt="Screenshot 2024-11-25 at 3 31 57 PM" src="https://github.com/user-attachments/assets/3770348d-2eac-4ead-a1df-199cf2047d4e">
<img width="435" alt="Screenshot 2024-11-25 at 3 41 15 PM" src="https://github.com/user-attachments/assets/e6535a71-fdd3-4562-a8bd-a2e1bcf6d3f1">


In this visualization, we created the same heatmap, but examined the percentage of arrests that make up a certain age group and gender going down all types of offenses, instead; in other words, how likely a certain age group and gender are to be arrested for a specific offense compared to all other offenses. This visualization allowed us to further our claim that NYC has prominent drug problems within their communities as we were able to see that all age groups and genders made up a significant portion of arrests for "Dangerous Drugs" compared to all the other types of offenses down the list. Moreover, we were able to gain deeper insights as to what types of offenses are females most likely to be arrested for. We found that Females in all age groups make up a significant proportion of arrests for "Assault 3 & Related Offenses" and "Petit Larceny", showing that these are the types of crimes NYC Females are most likely to be involved in throughout their lifetime. Using this information, the NYPD and the broader NYC community can build more youth programs, like youth camps and mentorships, aimed towards correcting adolescent behaviors that may lead towards potential arrests, especially stealing that is common among young women. 

## Question 2:

Question: Which boroughs are likely to see an increase/decrease in arrests over the next 6 years?

Importance: 

This question is important because it enables the police to be aware of the general trendline of crime or where crime is headed in NYC up until 2030. With this information, the NYPD can effectively allocate their resources, from officers and patrol units to crime prevention programs, to boroughs that might see a bigger increase in arrests than others. Boroughs whose arrests are expected to increase could receive additional personnel and increased surveillance, whereas boroughs whose arrests are expected to decrease could have their budgets and staff optimized to ensure that resources are not being wasted in areas with expected low crime. Additionally, NYC policymakers can utilize this information to make data-driven decisions and justify enacting stricter crime laws during expected periods of high arrests. This can greatly add to the broader goal of increasing transparency and building trust between the people of NYC and the policymakers and law enforcement. 


<img width="1440" alt="Screenshot 2024-11-25 at 7 23 16 PM" src="https://github.com/user-attachments/assets/9023c8e5-c081-4aff-9ac8-9e06242f3fa7">
<img width="1440" alt="Screenshot 2024-11-25 at 7 54 46 PM" src="https://github.com/user-attachments/assets/c8b384de-0623-4fd1-ba77-44c9295d2bc9">


In this visualization, we found that every borough of NYC, Bronx, Brooklyn, Manhattan, Queens, and Staten Island, is expected to see a slight decrease in the number of total arrests for the next 6 years. Based on the trend lines as shown, Brooklyn is the borough that is expected to have the biggest drop in arrests every month, whereas Staten Island is expected to have the lowest drop every month; however, this is mostly due to the small size and population of Staten Island, making it seem stagnant and acting as an outlier. One big factor that may be contributing to this drop in arrests could be the effects of COVID-19 in 2020, showcasing the lowest number of arrests of all time, but arrests have been increasing ever since then returning to normal levels. However, the drop could also be a sign of a big shift in law enforcement to crime prevention and proactive policing, rather than arresting and responding to calls after they have happened. This predictive analysis further justifies why the NYPD should emphasize proactive strategies which could be the key to lowering crime rates for the future as it will not only decrease arrests and increase the safety of every community, but also decrease the costs associated with arrests and reactive strategies overall, preventing the need for long investigations or court proceedings. Without this analysis, the NYPD won't be able to efficiently use their resources and live up to their expectations from the community.

## Manipulations applied to the data set for analysis:


<img width="155" alt="Screenshot 2024-11-25 at 8 30 16 PM" src="https://github.com/user-attachments/assets/799784e3-a988-4505-85a7-39e4d6d2b0c6">


Before analyzing our data and answering our questions, the data set needed to be cleaned due to many human errors present. For example, Ofns Desc contained a lot of duplicate values and spelling mistakes and Age Group had random numbers that didn't represent any sort of age group. So, we created "cleaned" sets for the following dimensions to filter out null, duplicate, or any unecessary data that they contained: Age Group, Perp Gender, Ofns Desc, and Arrest Boro. We also created a calculated field called "# of Arrests" which is basically the count of Arrest Key. These sets/filters and "# of Arrests" are used in both of our analysis. Overall, we have formatted our data and it contains no 3rd party imports.


<img width="447" alt="Screenshot 2024-11-25 at 8 45 14 PM" src="https://github.com/user-attachments/assets/7b4880b9-7b4a-472a-a6cd-eea8f850edeb">
<img width="445" alt="Screenshot 2024-11-25 at 8 45 59 PM" src="https://github.com/user-attachments/assets/d076cb5e-3884-4afa-82c7-40b0f88df6cb">


For our question 1 analysis, we performed 2 table calculations that turned the raw counts within the Heatmaps into percentages of the total number of arrests based on Age Group and Gender for each type of offense (% Across), and vice versa (% Down). The purpose of these table calculations was to ensure that we were evaluating the counts of arrests correctly for a specific Age Group, Gender, and offense when compared to others. For example, Males in the 25-44 Age Group had a high raw count of 36,668 of arrests for "Burglary" and a low raw count of 287 arrests for "Cannabis Related Offenses", but the proportion of arrests for "Cannabis Related Offenses", 51.07%, was greater than "Burglary", 40.95%, showing that Males are more likely to be involved in "Cannabis Related Offenses". 

<img width="1004" alt="Screenshot 2024-11-25 at 9 01 18 PM" src="https://github.com/user-attachments/assets/9849bd5b-12d5-4dd1-a3fc-4175f7228f1d">
<img width="505" alt="Screenshot 2024-11-25 at 9 04 23 PM" src="https://github.com/user-attachments/assets/ca2637b0-1f80-4e14-9fa2-8bea01f6a60b">


For our question 2 analysis, we utilized the Tableau's "Forecast" tool to predict the number of arrests up until 2030 along with a confidence interval for interpretation. Additionally, we applied Tableau's "Trend Line" tool to see the precise equation of how much the predicted line from the forecast tool was decreasing, as well as its R-squared and P-value.

## Tableau packaged workbook

The packaged workbook is attached via ELC (too big to attach to this)

## Presentation slide deck 

The slide deck is attached to this repository. 











