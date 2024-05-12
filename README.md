# Machine-learning_pipelines_predicting-blood-donations

We build a binary classifier to predict if a blood donor is likely to donate again within a given time window. We use the tpot library to find the best classifier and pipeline.

The data was collected from the donor database of Blood Transfusion Service Center in Hsin-Chu City in Taiwan. 

The dataset is a variation of the RFM model (Recency, Frequency, Monetary Value) used in marketing to categorise customers. The dataset is structured as follows: 

	• R (Recency - months since the last donation)
	• F (Frequency - total number of donation)
	• M (Monetary - total blood donated in c.c.)
	• T (Time - months since the first donation)
  	• Target variable (1 stands for donating blood; 0 stands for not donating blood)




