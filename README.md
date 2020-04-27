# Predicting-Viral-News
Problem Statement: Crawl and collect data from New channel website and predict whether a news is going to be Viral or Not. Solution:

Data-Outsourcing: What I implemented first is a crawler using BeautifulSoup and Request to crawl the websites and wrote the data into csv file, a example scrapper is present in the Fox-Scrapper. Likewise collected seperately news headlines and viral new from several news channel and stored them in to two seperate csv files. First in News.csv and the second one is Viral_news.csv which stores the Viral News Section.

Data-Cleaning: Implemented Data Cleaning using MS-excel.

Actuall Prediction: There are four coloumns in the both files and one extra label coloumn which contains whether it is viral or not. As all the fields contained text only, first i tried to get the number of clicks on each headlines within 30 mins,but was not able to get that data for that. So, left with text(Became a Classification Problem) fields only i decided to use TF_TDF(Term frequency-Inverse Document Frequency) to convert text in numerical data so it can be fed to the ML algorithms.

Algorithms Used: Logistic Regression, Support Vector Machine, GaussianNB.

Thanks Team @ Bipolar factory
