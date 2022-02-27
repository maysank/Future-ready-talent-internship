# MICROSOFT-FUTURE-READY-TALENT-INTERNSHIP 

# About Internship
This internship program wass a collaborative effort by various companies: Microsoft, GitHub, Ernst & Young (EY), Quess and Future Skills Prime. Different services were handled by different companies as given below:

Microsoft provided the learning modules and certifications to students. Learning modules will deal with trending concepts such as cloud computing, data, AI, and cybersecurity.
EY took care of the technological services and provide mentorship to students.
GitHub provided free access to GitHub Student Developer Pack.
Quess Corp provided students with an opportunity to showcase their skillset through virtual fairs.
AICTE helped to ensure that the curriculum is aligned to the National Education Policy(NEP), 2020.
SSC Nasscom ensured that the relevant courses are aligned with National Occupational Standards and linked these courses on Future Skills Prime.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Twitter Sentiment Analysis Logic App
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Problem Statement/Opportunity:
Identifying the sentiments of the tweets from Twitter regarding the current scenario of war between Russia and Ukraine. Understand the opinion of the Twitter users in terms of sentiment score.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Project Description:
What is sentiment analysis in twitter?
Sentiment analysis refers to identifying as well as classifying the sentiments that are expressed in the text source. Tweets are often useful in generating a vast amount of sentiment data upon analysis. These data are useful in understanding the opinion of the people about a variety of topics.

In this project, I tried to implement a Twitter sentiment analysis logic app that helps to overcome the challenges of identifying the sentiments of the tweets regarding the current scenario of war between Russia and Ukraine using MicroSoft Azure Services, To identify the thoughts of the twitter user in terms of sentiment score( positive/ negative/ neutral/ mixed), I per sentiment analysis on tweets and save them in Google Sheets. 

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Azure Technology:
1). Azure Cognitive Service:
Azure Cognitive Services enables you to build applications that see, hear, speak with, and understand your users. Between these services, more than three dozen languages are supported, allowing users to communicate with your application in natural ways. In this project I aquire it for Text Sentiment Anlysis on tweet text. 

2). Logic Apps:
The Azure Logic Apps platform helps you seamlessly connect disparate systems across cloud, on-premises, and hybrid environments. For example, In this project I cast Azure logic app in order to connect the text sentiment analyzer, Google Sheets and the twitter trigger.

3). Microsoft Azure portal:
thr whole project is built on the microsoft Azure portal, no other platform used.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# how did I do it?

In this project the platfrom which I aquired is Microsoft Azure portal. Firsty i headed towards the Azure Cognitive services to create a text analyzer which I later used to indentify the sentiments score of tweets. I created the text analyzer but I required a store the sentiment score somewhere, for which I cased google sheets to store the sentiment score with its corrosponding tweet and the user-name of the user who did that tweet. Next to connect the text analyzer the, twitter, google sheets. I used Azure logic apps. In logic app I first set the trigger in order to initialise the app, next I connect the text analyzer to indentify tweet sentiments, and final step was to connect the google sheet to store all the resulted analysis.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

