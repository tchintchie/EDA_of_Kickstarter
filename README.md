# EDA_of_Kickstarter
There’s a free dataset on Kaggle with Kickstarter project data from May 2009 to March 2018. Let's perform some EDA on the data (Exploratory Data Analysis) to gather any insights. https://www.kaggle.com/kemical/kickstarter-projects  
Note: the dataset is in a zip file with 2 csv files in it: 2016 and 2018. The data in both files is mostly the same but the 2016 one is older and uses a non-standard format, so for this let's just use the 2018 file only.  
## Questions to Answer: 
1. a. Examine the state column to see unique values and counts. 
1. b. Show a pie chart of the state project count for all projects. 
1. c. Create a new "Completed" dataframe that removes any rows with state of 'live', 'undefined', or suspended. note - from here out we'll be looking at the completed project data unless mentioned otherwise  

2. a. What is the overall success rate for all completed kickstarter projects?
2. b. Which 5 projects were pledged the most money (usd_pledged_real)? 
2. c. Which 5 projects had the most backers? 2d. Which year had the most competition? (# of projects)  

3. a. What is the success rate for all projects broken down by main_category? 
3. b. Show a horizontal bar chart for project success rate by main_category, sorted by highest to lowest. 
3. c. Within the Games main_category, what is the success rate for each category within it?  

4. a. Calculate the 'pct_of_goal' for each completed project 
4. b. What were the top 5 projects when looking at pct_of_goal for all time? 
4. c. Plot a histogram distribution of all completed projects by pct_of_goal 
4. d. Create 2 histogram subplots by pct_of_goal: 1) state=successful, and 2) all others (failed)  

5. a. What is the average usd_goal_real for all completed kickstarter projects, broken down by main_category. 
5. b. What is the median usd_goal_real for all completed kickstarter projects, broken down by main_category. 
5. c. What is the average usd_pledged_real for all completed kickstarter projects, broken down by main_category. 
5. d. What is the median usd_pledged_real for all completed kickstarter projects, broken down by main_category. 
5. e. What insights does this information provide? 
5. f. Based on this information, if someone wanted to choose the main_category with the highest combined success rate and pledged dollar amount, which one would you recommend?  

6. a. Create a new column 'months' that shows how many months the project was active between launch and deadline. 
6. b. Compare the avg months for successful projects vs non-successful. Add visuals if you'd like. 
6. c. Does the length of a project in months seem to have an impact?  Let's zoom in on Games: Video Games (main_category: category)  

7. a. Calculate the expected value for the Games: Video Games category, with the expected value defined as (median of usd_pledged_real)* (success rate of completed projects). 
7. b. Do this again but broken down by deadline year 
7. c. Show this in a bar chart 
7. d. What insights does this data provide you?  

### Let's zoom in on personal planners  
8. a. Calculate the project count, success rate, and pct_of_goal for all projects with 'planner' in the name. Check for spelling variations in upper/lowercase. 
8. b. How about all projects with both 'planner' and 'Panda' in the name? 



