# Capstone-project----DS-Intensive-Springboard
Capstone project
Project idea 1: Predicting/measuring success of start-up companies 
Story: Being interested in the VC industry, I always found it fascinating how some start-up companies manage to achieve huge success (get acquired hopefully at a high multiple, pursue an IPO), while other start-ups simply “disappear” (go bankrupt or get dissolved). For this project I am looking to measure a start-up firm’s success based on the following factors: choice of venture capital firm (each start-up generally would have several firms backing it), if any; timing of funding since the firm is founded; overall amount of funding received; and number of funding rounds. 
Model:
•	Dependent variable - binary: 1 if the company was acquired or went public, 0 if it got dissolved or went bankrupt
•	Independent variables: VC backers (1 if a specific VC firm is backing the start up or not); number of years between first funding round and founding date; amount of funding; number of funding rounds.
Challenge: Here, the difficulty that I currently foresee is in finding the right and comprehensive data for the project. 
Data: At this point, I intend to use the following data sources:
https://data.crunchbase.com/
https://www.kaggle.com/benhamner/y-combinator-companies
https://mattermark.com/
Perhaps, SEC/EDGAR, Form D filings
web scraping:
https://www.cbinsights.com/blog/startup-failure-post-mortem/
http://www.businessinsider.com/startups-that-failed-in-2015-2015-12/#homejoy-2 & similar articles
For story background:
https://www.quandl.com/data/NVCA-National-Venture-Capital-Association-Data




Project idea 2: Measuring terrorism using sentiment derived from Google searches and Twitter posts
Story: This is another topic that I am highly interested in. In my opinion, data is a great public safety vehicle and has the power to protect against terrorism. My hypothesis is that it’s possible to predict a terrorist attack based on how many “negative sentiment” searches and Twitter posts were made for a specific country in the months or years prior to the attack. On the other hand, negative sentiment needs to be “countermeasured” with the defense budget of a country, which has to be factored in to the analysis as well.
Model: 
•	Dependent variable - discrete: number of terrorist attacks in a specific country in a given year
•	Independent variables: number of “negative sentiment” Google searches for a given country in a lag year; number of “negative sentiment” Twitter posts for a given country in a lag year; defense budget of the country; country (dummy variable); year (dummy variable)
Challenge: The challenge is in identifying what the “negative sentiment” words are and in extracting that information.
Data: 
https://www.kaggle.com/START-UMD/gtd
https://www.google.com/trends/
Tweepy library on python
http://data.worldbank.org/indicator/MS.MIL.XPND.GD.ZS










Project idea 3: Identifying the best country to live in
Story:  I am curious to explore if 50 years ago, for example, we could have predicted that Norway and Sweden would have the happiest population of all the other countries in the world today. In retrospect, what determines the future happiest nation? In this project I would like to explore a relationship between multiple different factors, such as oil reserves, civil wars, foreign aid, military spending, literacy rates, corruption rates, etc. as compared to the happiness index 50 number of years into the future.
Challenge: Pulling all the relevant data together and designing a valid project out of it. 
Model:
•	Dependent variable - continuous variable between 0 and 10: well-being score for a given country and year
•	Independent variables: oil reserves 50 years prior; binary 1 or 0 variable for a civil war or any other war 50 years prior; amount of foreign aid received; military spending; country (dummy variable); year (dummy variable)
Data: 
http://data.worldbank.org/
http://happyplanetindex.org/countries
http://www.historicalstatistics.org/



