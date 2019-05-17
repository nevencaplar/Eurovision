# Predictor for the Eurovision victory, from the twitter data

This repository contains the main code used to predict Eurovision winner, based on the number of tweets that occur during the semi-finals. The main blog post is here: http://astrodataiscool.com/2019/05/predicting-eurovision-2019-from-twitter-data-draft/

The raw data is contained in the folder **Data**. **The Eurovision2019Data.ipynb** notebook contains the python code which was used in order to query the Twitter API and download the data, while the analysis has been done with **Twitter2019.nb**. 


Unfortunately the code is not very well documented, and certainly not in ``plug and go'' state. I still hope that it might be useful to someone to see the functions used, the logic and similar. If you are very brave you might try to run the code, in which case you will also need this file, that lists cities and their populations in different countries: https://github.com/CODAIT/redrock/blob/master/twitter-decahose/src/main/resources/Location/worldcitiespop.txt.gz. The data from this file are used in order to determine where are the Tweets coming from, based on the location string available for each Tweet. 