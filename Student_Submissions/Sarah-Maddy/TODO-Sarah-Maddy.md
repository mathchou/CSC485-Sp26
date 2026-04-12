PROJECT 1: 

1/23/2026

Goals for this week:

- [x] Create a file to store datasets
- [x] Find datasets that are relevant to answering our research questions 
- [x] Go through datasets to assess which ones are the most useful 
- [ ] Save datasets in a file so that they are easily accessible and try to save them in the same format (e.g., all excel sheets, all R codes)
- [x] Potentially start working on cleaning any datasets that have a lot of missing values, typos, remove and or add whitespace characters, etc.

Progress for this week: 

- We successfully created a way for us to share datasets with one another through a one drive folder
- We loaded all of the datasets from the project proposal into R Studio to view them in a table format, with the exception of the "weekly" dataset which seems to be giving some problems 
- We began cleaning the datasets that had a lot of repeating information and information that was not relevant to our particular research questions

2/1/2026

Goals for this week:

- [x] Continue to clean the data and check the accuracy of the information
- [ ] While we were cleaning some of the datasets we realized that some say Tom Brady's first name is "Tom" and others say "Thomas" so this disorganization will make it more challenging to perform analyses. We want to standardize the data by doing such things as assigning one id number to each player that is the same throughout each dataset 
- [x] Our data is mostly from 1999-2023 so perhaps we shrink our datasets by specifying what year range is exactly what we want 
- [ ] Once the data is clean, save the datasets in the file that we created
- [x] If time permits, start playing around with visualizations (preferably through PowerBI and Tableau)

Progress for this week:

- We continued to clean the data and check the accuracy of the information. This is taking longer than expected, so we are still working on this.
- We began to standardize the data sets so there are common ids throughout each that can be used to compare.
- We started to narrow down the data sets by specifying what year range we want to work with. We decided to work with 2001 - 2023 because this is the timeframe that Tom Brady was a starting quarterback in the NFL
- We started a variable list holding descriptions of exploratory variable within our data sets for analysis.
- We created a Power BI dashboard to begin testing out visualizations. We uploaded our first clean data set into the dashboard.
- We began a quarterback specific data sets to combine data

2/8/2026

Goals for this week:

- [x] Continue to clean the data and check the accuracy of the information
- [ ] Continue standardizing the data by doing things such as assigning one id number to each player that is the same throughout each dataset
- [x] Continue uploading the cleaned datasets into the Power BI Dashboard as they are complete
- [ ] Consider creating a master data set that merges all the data into one excel sheet
- [x] Continue working on the quarterback specific data set to combine the data

Progress for this week:  

- We were able to merge datasets in meaningful ways and started to develop ideas for how we are going to analyze them all together (e.g., doing a regression analysis on weather to see how it impacts player performance) 
- Example of our process of assessing models: when analyzing the weather, found that temperature is a bad predictor of the total score for each game, meaning that the temperature has no impact on how high or low scoring a game will be (p-value = 0.7861) so it does not hinder player performance significantly 
- Worked with PowerBI to visualize the data, which revealed some additional issues in the datasets such as missing values and column headers in R being the first rows of the excel sheets, so we fixed those errors when necessary 

2/15/2026

Goals for this week:

- [x] Continue working on regression analysis, preferably through R Studio 
- [x] Analyze the summary of each model developed and check for association and correlation between variables (r^2 and r), statistical significance (p-values), etc. 
- [x] Plot regression models and store the visuals in some manner (make a big pdf, slideshow?)
- [ ] Start working on practically interpreting values for a report 

Progress for this week: 

- We worked on running regression models specifically for environmental conditions influencing such things as how high scoring games are and passing yards
- Had to modify some of the data like creating columns of averages and grouping by such things as teams, players, etc. which yielded more statistically significant results when we analyzed the summaries 
- We created graphics to help visualize this data in R such as simple scatter plots, line plots, and correlation matrices 
- We created more sub datasets holding EPA information
- We found the 5 quarterbacks with the highest average career EPA
- We started creating line plots and scatter plots to visualize this information 

2/20/2026

Goals for this week:

- [x] Start to wrap up any final regression models we want to explore 
- [x] Practically interpret summary outputs for our report 
- [x] Create presentation and decide what information we want to highlight to share to the class
- [x] Continue creating visuals to compare QBs EPAs
- [ ] Calculate QB EPA for playoff games to represent how QBs perform in high stake games

Progress for this week: 

- We finished wrapping up regression models and other results 
- Calculated a standardized G.O.A.T. score that will help us conclude that Tom Brady is the greatest of all time 
- Started our presentation to be delivered on Monday 

2/27/2026 

Goals for this week: 

- [x] Conclude this project by combining all of our results together
- [x] Give our presentation and write our paper 

Progress for this week: 

- Successfully completed our first project 

3/5/2026

Goals for this week: 

- [x] Start thinking about what we want to do for project 2

Progress for this week: 

- Presented our project proposal and began work on collecting our data



PROJECT 2: 

3/27/2026 

Goals for this week: 

- [x] Create a file to store datasets
- [x] Refine research questions to focus more on competitors
- [x] Continue to find datasets that are relevant to our research questions
- [ ] Import all datasets into R and clean them
- [ ] Potentially start working on cleaning any datasets that have a lot of missing values, typos, remove and or add whitespace characters, etc.

Progress for this week:

- Refined our research questions and data to focus more on Chipotle's competitors and customers
- Created a file to store datasets
- Manually combined datasets together in excel by year and started to import the datasets into R

4/7/26:

Goals for this week:
- [x] Continue to import all the datasets into R
- [x] Begin to clean the data and find ways to merge more complex datasets together 
- [ ] Possibly start performing an exploratory data analysis and create visuals for the data

Progress for this week: 
- Successfully loaded the csv files and scrapped the other files from the web
- Cleaned the main datasets that we will use (chipotle financial data, store locations data, and U.S. population data)
- Filled in missing values by fitting a line to each column and predicting the past values 

4/12/26:

Goals for this week: 

- [ ] Perform an exploratory data analysis and create visuals 
- [ ] Research why there are drops in some of the financial data to try to explain it better
- [ ] Start performing regression models, random forests, etc. 
