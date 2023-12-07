# ANALYSIS OF RUSSIAN PROPAGANDA ON TWITTER

## Introduction

Twitter is the best place for fake news and propaganda topics to start and evolve, especially because of Twitter censorship policy. Most often, 
topics from Twitter are taken over by ordinary trolls and shared on Facebook for much faster spreading. This makes Twitter the place where the 
most experienced and important accounts of Russian propaganda machine makes the narrative thread for new fake news to be spread to the public.

This study aims to find insights about how the Russian propaganda machine is working in terms of how disinformmation is created, spread and how 
is targeting the audience.

For this study, I chose 28 of the most well - know Russian propaganda Twitter accounts:

* RosettaNews247 - https://twitter.com/RosettaNews247
* RT_com - https://twitter.com/RT_com
* LumpyLouish - https://twitter.com/LumpyLouish
* Levi_godman - https://twitter.com/Levi_godman
* RWApodcast - https://twitter.com/RWApodcast
* Taurevanime - https://twitter.com/Taurevanime
* realGonzaloLira - https://twitter.com/realGonzaloLira
* Russ_Warrior - https://twitter.com/Russ_Warrior
* SNMilitary - https://twitter.com/SNMilitary
* GeromanAT - https://twitter.com/GeromanAT
* thesiriusreport - https://twitter.com/thesiriusreport
* RussianEmbassy - https://twitter.com/RussianEmbassy
* gbazov - https://twitter.com/gbazov
* colonelhomsi - https://twitter.com/colonelhomsi
* Vick_top55 - https://twitter.com/Vick_top55
* PelmeniPusha - https://twitter.com/PelmeniPusha
* Alexxa1721 - https://twitter.com/Alexxa1721
* jacksonhinklle - https://twitter.com/jacksonhinklle
* GarlandNixon - https://twitter.com/GarlandNixon
* AngieSkys - https://twitter.com/AngieSkys
* NinaByzantina - https://twitter.com/NinaByzantina
* Tinkzorg - https://twitter.com/Tinkzorg
* mfa_russia - https://twitter.com/mfa_russia
* RussiaUN - https://twitter.com/RussiaUN
* A__Alimov - https://twitter.com/A__Alimov
* mission_russian - https://twitter.com/mission_russian
* rusembusa - https://twitter.com/rusembusa
* StalinFrog - https://twitter.com/StalinFrog

## Workflow

1. Data collection;
2. Data preprocessing, formating and cleaning;
3. Exploratory analysis & descriptive statistics: views, retweets, replies, likes, hashtags, photo/video usage, accounts & tweets exploration, time series analysis;
4. Sentiment analysis: tweets preprocessing, Naive Bayes classifier, clustering (K-Prototypes);
5. Daily summarization: extractive text summarization;
6. MongoDB daily ingestion;
7. Conclusions.

## Conclusion

I've decided to add the analysis conclusions here to provide more context to the project.

* the most successful topics of propaganda are those that present the **so-called imperialist ideology of the United States, the presence of Nazism in Ukraine and the devastating effects of the war on the European economy**;
* each tweet is viewed by **6000** people on average (on a first instance) and retweeted by almost **60 times** (on average). This ensures a very high spreading of the Russian propaganda on Twitter;
* The most used hashtag in Russian propaganda is **"#zakharova"**. Maria Zakharova is the Director of the Information and Press Department of the Ministry of Foreign Affairs of the Russian Federation. This could indicate that Russian fake news and propaganda is dictated by Russian government itself. Another relevat hashtag used by these accounts to support the propaganda thesis is #naziukraine;
* the most active account is **GeromanAT** which posts daily news about the stage of the battles in Ukraine, focusing on a subjective interpretation of events and omitting any information that presents the serious problems that Russian army is facing; The most viewed account is **rwapodcast**, which has a negative sentiment score, indicating the use of hate speech to spread propaganda topics;
* the **official Twitter accounts of the Russian government** have the lowest activity among all the accounts that promote fake news. However, they surprisingly enjoy the most interaction with the target audience, as evident from the high number of replies on their tweets;
* the general trend is **not to use pictures or videos** in their posts. As a comparision, professional media agencies always use pictures to support the authenticity of the presented events;
* as media attachments, they often use videos instead of pictures, videos **created in such a way to cause feelings among their target audience**;
* **jacksonhinklle** is the most popular propaganda Twitter accounnt with the most views of tweets, with an average of 30000 views/tweet. Jackson Hinkle is an american political commentator and YouTube streamer, whose commentary focuses on anti-imperialism and other populist topics. He is spreding russian propaganda on Twitter because it fits his ideas; (but some evidence that has appeared in the public space suggests that he is paid by the Kremlin);
* **the general sentiment of Russian propaganda is a neutral one**; But this is due to the fact that Russian government pages (which have an above-average positive score) pull up the overall sentiment score values. Most probably because, posting from an official position, you are somehow forced to use formal positive language;
* More than half of the accounts, 14 in number **(alexxa1721, garlandnixon, geromanat, jacksonhinklle, levi_godman, lumpylouish, pelmenipusha, realgonzalolira, russ_warrior, rwapodcast, snmilitary, taurevanime, thesiriusreport, tinkzorg)**, have a negative sentiment score. This once again demonstrates the use of hate speech in spreading the propaganda. Moreover, over time, the sentiment score continues to decline among these accounts due to the Russian army's failures in Ukraine and the firm measures taken by the West;
* On the days when the Russian army commits serious war crimes that are exposed to the public, **these accounts become more active**. This increased activity is likely an attempt to discredit news that involves the Russian Federation.
