# British Airways Virtual Experience Program
## About The Programme:
During this programme, participants have the opportunity to step into the shoes of a British Airways team member and complete tasks that replicate the work that British Airways' Data Science team does every day. The goal of this programme is to learn how to scrape customer review data and build predictive models.
## First Task - Web scraping to gain company insights
**The Goal:** The focus of this project was to collect data, perform quick data exploratory analysis (EDA) and sentiment analysis, and finally present insights within a single PowerPoint slide. Estimated time for task completion was 1.5 hours<br /><br />
**The problem:** British Airways (BA) is the flag carrier airline of the United Kingdom (UK). The end-to-end process of scheduling, planning, boarding, fuelling, transporting, landing, and continuously running flights on time, efficiently and with top-class customer service is a huge task with many highly important responsibilities. Customers who book a flight with BA will experience many interaction points with the BA brand. Understanding a customer's feelings, needs, and feedback is crucial for any business, including BA.<br /><br />
**The solution:** First, I needed to collect and scrape data from the website https://www.airlinequality.com/. The team leader wanted to focus on reviews specifically about the airline itself. When the data was clean, I had to perform analysis to uncover some insights. To do so I considered to perform sentiment analysis to provide some insight into the content of the reviews.<br /><br />
**The process:**
1) Web Scraping (Using Beautiful Soup package)
2) Quick EDA (Exploratory data analysis)
3) Sentiment Analysis (2 approaches, which then were compared)
4) Present insights (within 1 PowerPoint slide)
## Second Task - Predicting customer buying behaviour
**The Goal:** The focus of this project was to build a binary classification model that is able to predict a customer making a booking. Furthermore, we should create a visualisation to interpret how each variable contributed to the model. Finally, we should summarise findings in a single slide to be sent to the manager. <br /><br />
**The problem:** Airlines must be proactive in order to acquire customers before they embark on their holiday. This is possible with the use of data and predictive models. With a predictive model, it is important to interpret the results in order to understand how “predictive” the data really was and whether we can feasibly use it to predict the target outcome (customers buying holidays). Therefore, we should evaluate the model's performance and output how each variable contributes to the predictive model's power.<br /><br />
**The solution:** If the model could tell the company who amongst customers will more likely make a booking, we could create a focus group for that customers who may just need a little more attention and push to finally make a booking. So we need to be able to distinguish them first, and that is where our model comes in.<br /><br />
**The process:**
1) Explore dataset (EDA)
2) Prepare the data
3) Train a machine learning model
4) Evaluate model
5) Present findings<br /><br />
**The Metrics:** For the metrics I chose Accuracy Score and the ROC AUC Score.<br /><br />
**The Baseline Model:** The baseline model was the Random Forest Classifier because it handles imbalanced data and easily allows us to output information about how each variable within the model contributes to its predictive power.<br /><br />
**Gradient Boost & AdaBoost:** These two methods fall under the ensemble category of modeling. I wanted to give the two models a try to see how they would perform.<br /><br /> 
**Conclusion:** The Random Forest Classifier has given us the best results when predicting the target.<br /><br />
# Repositoy Guide
**Notebooks**<br /><br />
First Task https://github.com/UssinaSabina/British-Airways-Virtual-Experience-Program/blob/main/Notebooks/BA(1).ipynb<br /><br />
Second Task https://github.com/UssinaSabina/British-Airways-Virtual-Experience-Program/blob/main/Notebooks/BA(2).ipynb<br /><br />
**CSV files**<br /><br />
Raw scraped data https://github.com/UssinaSabina/British-Airways-Virtual-Experience-Program/blob/main/CSV_files/raw_BritishAirwaysReviews.csv<br /><br />
Cleaned scraped data https://github.com/UssinaSabina/British-Airways-Virtual-Experience-Program/blob/main/CSV_files/pretty_BritishAirwayReviews.csv<br /><br />
Only Text Reviews https://github.com/UssinaSabina/British-Airways-Virtual-Experience-Program/blob/main/CSV_files/textReviews.csv<br /><br />
Provided dataset for the 2nd task (contains data about customer booking) https://github.com/UssinaSabina/British-Airways-Virtual-Experience-Program/blob/main/CSV_files/customer_booking.csv

