# Crimepredict
The end goal of the project was to help 911 officials predict a crime type and dispatch forces accordingly.
We had a dataset of the Cincinnati crime data with 40 variables. A few of them are Incident ID, Date reported, Date To, Date from, Closed duration, UCR group, Offense type, Zip code, Victim Gender, Victim Race, Suspect Race, Suspect Gender, Weapons.
We cleaned and pre-processed the data so as to only work with significant variables while still maintaining its integrity.
The final dataset consists of 32 variables. To further analyze variables affecting crimes, we plotted the L_code vs offense, Month vs offense, Month vs UCR group, Day of week vs offense, Day of week vs UCR group, count of clsd_des vs the offense type to get a visual sense of the data. The affected areas in Cincinnati region were showed using a heat map.
For our Supervised learning, we built a Decision tree to show the Closed code and the UCR group rules that are factors for the crime data predictions.

We then did logistic regression that predicted the most affected areas in the Cincinnati region, plotted a Time vs Crime Bar plot to see at what time of the day most of the crimes were committed.

We also analyzed which areas are mostly affected as per the crime data analysis.
