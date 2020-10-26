# eTe-analysis

This is the Assessment Task II Project by UTS MDSI students in Spring 2020

Project Title: Collaborative Development of an end to end project using Centralized Code Repositories + Github usage analysis and reflection of the project

# The file structure is 

/raw_data - Store all the raw data files

/etl - for Extract, Transform, Load processing

/analysis - for code of EDA and insights

             /analysis/question_1 - for  each research question
             /analysis/question_2
             /analysis/question_3
             
             
 # Data 
 The raw dataset is about Mental Health and Suicide Rates
 There are five csv files:
 * source : https://www.kaggle.com/twinkle0705/mental-health-and-suicide-rates?select=Human+Resources.csv 
 - age_standardized_suicide_rates.csv : Age standardized suicide rates for different years
 - crude_suicide_rates.csv : Suicide rates(year 2016) per 100000 population in different age range
 - facilities.csv : Facilities available of different countries in 2016
 - human_resources.csv : Human resources available of different countries in 2016

* source: https://data.worldbank.org/indicator
- socioeconomic_indicator.csv: the latest poverty rate and GINI coefficient (income inequality) per country

* source: https://data.world/afterschool/teen-stress-mental-health-poll-on-after-school/
- mental_health_poll_updated.csv: survey on 35.000 teens regarding their stress and mental health, along with actions they take in times of need
 
 # How to start ?
 - Fork this repository to your personal remote repository(account)
 
     This will be your own remote repo to which you push your locally committed changes and 
     from which (browser interface) your pull request will be made.
 
 - In your local machine, create local repository, 
    in your preferred workspace,
    
      git init
      
 - Connect to your personal remote repo from your local repo
 
      git remote add origin master https://github.com/xxxxxx/eTe-analysis.git
 
 - Clone your remote repo into your local machine
 
      git pull origin master ("clone" also works)
      
  Then every thing is ready. So there are altogether three stages of repository.
  
  local repo --> personal remote repo --> master central remote repo
 
 
 # General Rule of Thumb in Creating Tasks, Assigining Tasks and Making Pull Requests
 
- Use "Issues" tab to register the tasks to which member(s) are assigned or your favourite tasks assigned to yourself
- State Issue Id  "#xx" in the pull request name / title/ message to allow the teams knows that what your Pull request is about and to which task(issue) it is for

# How to keep your local repository updated everyday? Important!!!!

- Make sure you commit your local changes first
- Always make git pull before starting your work of the day in your local directory/repo

    git pull https://github.com/mdsi-dsp-at2/eTe-analysis


