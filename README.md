# DS-Project1-Scraping
Webscraping using BeautifulSoup to get job related data and use random forest to predict job titles

Introduction:
Webscrape job skills data and use the skills listed to predict job title that is Data Analyst or Data Scientist

Description:
I chose to webscrape Dice.com using BeautifulSoup, the extracted features included:
    a. Job title
    b. Location
    c. Company Name
    d. Required Skills
    
I used CountVectorizer to extract features from the Skills description and then used RandomForestClassifier for predicting the Jobtitle

Files:
1.dicedata.csv
2.JobDataScraper.ipynb
3.JobTitlePredictor.ipynb
