# Gartner-Hackelite-Client-Retention-Status
Gartner Hackelite Client Retention Station


https://www.hackerearth.com/challenge/competitive/gartner-hackelite/problems/

https://www.hackerearth.com/challenge/competitive/gartner-hackelite/leaderboard/

# Problem Statement 

On Thursday, May 5, 2018, Alexander the Great, XVII, Senior Vice President from Gartner Product & Services business division slumped on his seats in the evening flight from Fort Myers to Stamford. He had just completed fifth operations meeting with the executive board of Gartner Inc. Alexander has been given a responsibility to think through the performance metrics of his service team that would collectively improve the retention of products. Currently, the service teams work with a multitude of goals, that may or may not lead to higher retention as an outcome, hence it imperative he pulls together the past performance data and reflects on what goals are truly important.


He reached New York Airport and during his road journey from New York airport to his home in Stamford, he calls his colleague in India, Valini to devise a strategy to develop a model with her data science team to define what goals a service team member should have that can help drive higher retention. He also shared his initial hypothesis around goals that are likely achievable and can enable the service team to drive retention. E.g., higher frequency of meetings with clients, consistent usage of Gartner documents, and attendance at Gartner events was the top of his mind ideas on what could drive client retention.


Imagine you are a Data Scientist in India team who has been given the past performance data for a service team uniquely supporting the product in question, and are asked to create a predictive model that utilizes the most actionable features or performance drivers to elevate the end outcome: client retention.


As a lead for the team, your recommendations around the following questions will enable Alexander to make a business case for redefining the goals of the service team for 2019. Valini has tasked you to focus on following questions.


What are the most important features (variables) for confidently predicting client retention?  Impact retention with a high degree of confidence


What is the most important variable affecting retention and what will be its impact on retention?


Identify additional variables which impact retention


What is the accuracy, sensitivity, and specificity of the model that establishes confidence in our results?


## Data Set Description

You are provided with an anonymized dataset containing information regarding the client. Train.csv file contains data for training a model.Test.csv file contains data for which retention status need to predicted and submitted to the portal.


Data Column Definitions are given in the data_dictionary.csv file. 


Download the Dataset 


An initial hypothesis as suggested by Alexander
Some of the indicators of high client engagement in past are document usage (no. of document read), inquiries made, views on Gartner social media and attendance at Gartner events (Hint: Client engagement can be the function of the combination of multiple of this activities)


Combination of one or more than one of these indicators can be predictive of retention.


If a client is not eligible for inquiry, he/she can purchase inquiry anytime. This can be an indicator of higher engagement resulting in higher retention.


Presence of these indicators in specific months (or month) can be predictive of retention; e.g., document usage in the first three months could be a predictor of retention; document usage in the 11th month could be a predictor of engagement.


The frequency of these indicators could be predictive of retention; e.g., at least one event attendance in the contract period could be a predictor of retention, at least two document usages in a month could indicate retention


Client sharing value statement has a higher probability of getting retained


Service levers such as kick-off a call, regular service call, and onboarding could be predictive of higher retention.


Recency and consistency of client activity (i.e., document usage, inquiry done, social media and event attended) may have an impact on client retention


## Some useful information for the case


Each Gartner product enables its clients to use the following services during their subscription period*


Documents (these are publications available on the Gartner website that clients can read basis their interest)



Inquiry with Gartner analyst (these are dedicated sessions that clients can do with experienced thought leaders called analysts; Client can talk to Gartner analyst and can take help in solving key problems they are trying to solve in their business. Gartner analyst is usually with 20-35 years of industry experience)


Gartner Peer Connect is the Social media for Gartner clients


Events - Conference and Symposium – are Gartner organized meetings with a large group of attendees


Gartner schedules events across the globe for business leaders. There are two types of events: ‘conference’ which is usually attended by business heads, VPs, Director etc. and second, ‘symposium’ which is attended by CIOs


Gartner clients can avail subscription for document usage with Inquiry, Gartner Peer connect or Event


The frequency of document usage, an inquiry is done and social media view in the nth month is given in the data sheet.


Gartner clients can take single year subscription or multi-year subscription


When clients take the subscription, Gartner consultants schedule onboarding and service kick-off calls/meeting with them. Gartner service helpdesk helps Gartner clients in using Gartner service in most efficient manner. Gartner service helpdesk tries to schedule calls with the client every month.


Clients can share testimonials regarding how Gartner helped them in solving their problem; we call this ‘Value Statement’


## Evaluation

The predictions are evaluated as the weighted sum of the following three metrics:

Specificity


Sensitivity


Accuracy


The leaderboard score is generated as follows:


Score =  (0.5 * Specificity) + (0.3 * Sensitivity) + (0.2 * Accuracy)
