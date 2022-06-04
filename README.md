# Correlation-between-ESG-Sentiment-and-Financial-performance-of-DAX-companies
The Version 1.0, Version 2.0 and Version 3.0 folders contain code for the analysis of performance metrics for the transformer models DistilBERT, FinBERT and roBERTa. 
Version 1.0 contains the files for the original dataset ('esg_sentiment_data.xlsx')
Version 2.0 contains the files for the corrected dataset ('esg_sentiment_data_corrected.xlsx' - Corrected 'true_sentiment values')
Version 3.0 contains the files for the next dataset(bigger dataset of 67K records) - The fine-tuning of the roBERTa model is performed on this dataset. The preparation of training dataset, balanced dataset, shuffled dataset all for the purpose of fine tuning is done here. 
The 'Fine tuning' folder contains the code for fine tuning the model and saving the model for future use. 
The 'Trained_Models' folder contain the daved fine tuned model. 
The Data, Data1 and Data2 folders contain the actual input data obtained from Equintel.
The 'MyModules' folder contains the .py file for company name recognition of concept, surface and ambiguous forms.
The 'Analysis' folder contains the files for the analysis pipeline, calculation of historical data and calculation of ESG sentiment data. 
The Results_date folders contains the results obtained as part of the analysis pipeline from the three sets of data. 
The ESG_Sentiment folders contain the ESG sentiment data calculated for each company for each day. 
