# BSPL Interventions Project
In the first file NormEvidenceInterventions.rmd, the first thing I did was try to regress Chosen Topic ~ Topic Importance. 
The most important regression I found was this: 

![image](https://github.com/AaronDantzler/InterventionsProject/assets/113250815/25e4d27e-b5c0-4ffc-a1d8-a78a0a00a888) 
This uses a multinomial logistic regression model, and the interpretation is that an increase of the importance of a topic significant predicted the topic being chosen, which makes sense. I then tried regressing both Chosen Topic ~ Time and Topic Importance ~ Time but did not find a significant relationship. I also tried regressing both Chosen Topic and Topic Importance on Treatment, which we might expect Treatment to increase Topic Importance and the probability of a Topic being Chosen, but I did not find a significant relationship.
In the second file, normsANOVA, I tried to see if Treatment or Time had a significant relationship on Topic Importance (which have seen previously that Topic Importance has a strong positive relationship with Chosen Topic). However, using a two-way repeated measures ANOVA, there was no significant difference between the means of the treatment groups over time. 
![image](https://github.com/AaronDantzler/InterventionsProject/assets/113250815/df64f9ff-2929-4a1f-8a39-44ca9d96db3b)
The next file, DTMSentimentAnalysis.rmd is me taking the survey FRQ responses we have and using both the bing and AFINN lexicons to assign sentiments to the words and the overall combined sentiments of each FRQ response. The bing lexicon assigns words to either positive or negative, while the AFINN lexicon assigns a word a number between -5 to 5, going from negative to positive.
The next file, SentimentRegressions.rmd was trying to see if there was a relationship between the overall sentiment of an FRQ response and the time it was written and condition each respondent was given. While I did not find a significant relationship with time, there were significant relationships for each type of treatment: 
![image](https://github.com/AaronDantzler/InterventionsProject/assets/113250815/3cb7d35b-7be7-436f-a330-c477c69ba314) ![image](https://github.com/AaronDantzler/InterventionsProject/assets/113250815/8c05fade-8e8b-4185-85f3-2ea5b2f22f2a) 
In particular, treatment lowered the overall sentiment of a response, with normevidence lowering sentiment the most, followed by evidence and then norm. This relationship appeared using both the bing and AFINN lexicons.
The next file is Visualizations.rmd, where I tried to use a variety of more qualitative visualizations to view patterns in the FRQ responses (I included models that include all of the data, but I felt it was more sensible to look at each topic on its own so that the data was not getting crosscontaminated). Looking first at the Climate Only Data - this graphic shows different words that stood out between the treated vs untreated groups: 
![image](https://github.com/AaronDantzler/InterventionsProject/assets/113250815/742682fb-cd90-4d2b-a48c-97052156585c) 
It seems like the treatment made people talk more about things like shopping and air travel. 
The most negative word that sticks out in both the treated and untreated group is waste, while more common positive words were words like protect and support. ![image](https://github.com/AaronDantzler/InterventionsProject/assets/113250815/6c66b827-7b86-40d1-8517-dfdb56db6dd7) Overall, the most common things that everyone talked about were plastic bags. 
![image](https://github.com/AaronDantzler/InterventionsProject/assets/113250815/851e9cad-3c6d-4875-93b9-826db03a48c1) 
Treatment also made people use more negative words such as garbage and degrade, as well as focusing on the human impact on the environment. 
![image](https://github.com/AaronDantzler/InterventionsProject/assets/113250815/94f50ac3-262d-4559-b6e8-cae0785d95d1)
Now looking at the Health Only Data - words that tended to stick out among the treated group were things like drunk driving and alcohol. 
![image](https://github.com/AaronDantzler/InterventionsProject/assets/113250815/a7449400-5a1b-468d-9cf3-e6bafa8b602d) 
Drunk was by far the most common negative word used in the responses. 
![image](https://github.com/AaronDantzler/InterventionsProject/assets/113250815/dba6db59-6e18-4764-a0a0-ded8ebdc2f95) 
Among all responses, mental health were most common words used, as well as drunk driving, althought still more in the treated than the untreated group. 
![image](https://github.com/AaronDantzler/InterventionsProject/assets/113250815/469352d9-01e7-477d-a5bb-7d1b93db5b71) 
Words that stuck out that were only used mainly in the treated group were words such as Uber, preventable and impaired, which also align with people's concerns over drunk driving and ways it can be curtailed. 
![image](https://github.com/AaronDantzler/InterventionsProject/assets/113250815/336427ee-9866-4c2d-a224-6e217aa6e4b0)
Looking now at the Politics Only Data - words the treated group tended to emphasize were more about the economy and its effect on people, with words such as bills, money and minimum wage, while the untreated group focused more on explicitly political words like democracy and elections. 
![image](https://github.com/AaronDantzler/InterventionsProject/assets/113250815/9544418a-edd6-4216-a32e-cf2b5d449f42) 
People overwhelming used the words people and minimum wage when discussing these topics. 
![image](https://github.com/AaronDantzler/InterventionsProject/assets/113250815/6ab8c6ae-1377-467a-99d7-7c2a89741faa) 
Additionally, the treated group tended to focus on more economic words such as tax and expenses. 
![image](https://github.com/AaronDantzler/InterventionsProject/assets/113250815/6464c7af-978f-4d94-917c-35864634daa8)
The last file is normsSTM.rmd






  


