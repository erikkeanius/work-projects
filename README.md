Many of the projects I have worked on were done at companies. Below you can find a small sample of some of the projects I have done, with more detailed descriptions. However, the code and properietary information cannot be shared. Please note that this is by no means an exhaustive list of what I have worked on.

**NLP and high dimensional clustering**

How can you match records between different parts of an internal database? One part of the database was maintained by the sales department containing purchasing and buyer information, and one part of the database was maintained by the engineering team containing user information. One buyer could have many users (e.g. Company A bought the product and could then have user A, user B, user C etc.). For sales people there was a need to couple the two parts in order to match buyer behavior with user behaviour, i.e. there was a need to match users to buyers. To achieve this, I developed a method based on NLP fuzzy matching and high dimensional clustering. This allowed sales department to target potential churners and more easily up-sell products to correct customers.

**Time series forecasting for ads**

How do you forecast ad match rates? The company I worked for had an internal mediation system for ads. The goal was to forecast the ad match rate at the cohort level, and use that as a proxy for the ad demand: higher match rate would mean higher demand and thus can set price levels higher for traditional networks to bid at. To do this, I created different time series models, among others, tree models and LSTM neural network to forecast the match rate. This ultimately made the work of people in the ads team easier and allow them to make better decisions. 

**Anomaly detection for quality control of incoming data**

How do you ensure quality of the incoming data? The division lacked a systematic way of looking at incoming data quality. Prior, the data quality control had been ad-hoc, and problems were often not identified until days later, which created stale and unreliable data. Thus, I decided to change that. Using anomaly detection, I created a model that would send an alert when a pipeline took an unusual amount of time to finish (either too long or too short time) or when then the number of new data points was unusual. This lead to faster troubleshooting and fixies, more accurate data, and less downtime of business critial data.

**Model word-of-mouth effect using time series**

How do you measure the word-of-mouth effect of a product? If Alice presses an ad and joins, she is regarded as a paid member (a member acquired through user acquisition), but if she tells her friend Bob about the product and he starts using it, he will be classified as an organic member (a member not acquired through user acquisition). In reality, there is an argument that he should be attributed to the campaign as well, and if he is not, then the ROI of the user acquisition campaign is lower than what it should be. To measure the effect, I modelled this using an ARDL model. Under some assumptions (mainly the stationarity of the time series or co-integration of the time series), one can calculate the long-run effect of one of the time series on the other, which is the word-of-mouth effect. By controlling for this when evaluating the performance of user acquisition campaigns, the ROI became more accurate and reliable, which allowed the user acquisition team to make better decisions.

**Statistical methods applied to economic research**

“Does policy changes affect companies access to capital and level of innovation" and “Does the European Emission Trading System lead to more innovation”. These were two of the questions I worked on at this specific governmental institutionen, with implications for both policy makers and economists. By using novel data sets and econometric methods for time series and regression, it was shown that there was an increase in green innovation while access to capital had not changed.


