# Autoencoder-Based-Approach-for-Cancer-Subtype-Prediction-Intratumor-Heterogeneity-level-Estimation
Autoencoder Based Approach for Cancer Subtype Prediction &amp; Intratumor Heterogeneity level Estimation Using Multi Omics Data
This Repository contains the Autoencoder Based Approach for predicting the Breast Cancer Subtypes & the Intrarumor Heterogeneity Level Estimations of Stages . This  shows hoe thw work flow the analysis on the Four datasets of RNA Seq , Gene Mutations , DNA Methylations & Clinical Data Using the Autoencoder Model to predict the Cancer stages for better Prognosis.
Initially the Datasets of RNA Seq, Gene Mutations & DNA methylation are combined with the Clinical Data which has been converted in to Numerical format using Label Encoder to get the Important features. 
Boruta Feature Algorithm with Random Forest Classifier - performed on each Individual set to get the Important Features are extracted to CSV file.
RNA Seq , Gene Mutation , DNA Methylation with the confirmed Features coming from The Feature Selection Algorithm are Used for effect of downstream Analysis.
Normalization - This is used to scale the Data, performed on RNA Seq & DNA Methylation Data to have the Equall Range of Distribution. 
Merged Datafram - The Above three Data set are merged using join Function one after the other & later with Clinical Data containing Cancer subtypes.
Data Split - This Merged Dataframe has been split into Train & Test sets for the Machine Learning Model of Autoencoder.
ML Model -  Autoencoder is used to stream the analysis, to see/ Learn the Latent Representations of the Data. 
Finally, the output of extracted Features from the output of Autoencoder is used to Visualize & predict the Intratumor Heterogeneity Level.
