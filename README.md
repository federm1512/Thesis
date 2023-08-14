---
Deciphering Online Consumer Behaviour: A Network Analysis and Multivariate Time Series Study on Amazon Reviews
---

The code used for this thesis is in the following 4 Jupyter notebooks and it is structured as described bellow:


## 1. data_engineering_thesis
This notebook contains all the code for preparing the dataset used in the study.
	- Loads the datasets (data and metadata)
	- Prepares the dataframes and merges them into a unique consolidated one
	- Preprocesses the datasets for them to be used in the subsequent analysis

## 2. EDA_thesis
This notebook contains the Exploratory Data Analysis.
	- Offers a comprehensive overview of the data's characteristics and distributions, providing insights into potential patterns and areas of interest for further research.

## 3. Hier_VAR_thesis
This notebook contains all the code for answering the first research question, using hierarchical clustering and VAR models. Structure is as follows:
	3.1 Preprocessing: Prepare the time series data for the clustering algorithm
	3.2 Hierarchical Clsutering: Perform hierarchical clustering within each category
	3.3 Aggregation: Create a single time series for each cluster
	3.4 Var Modelling: Fit a Var model to the cluster time series
	3.5 Validation: Validate the model

## 4. Epidemic_models_thesis
This notebook contains all the code for answering the second research question.
	- Creates the Amazon review network
	- Computes the graphs metrics
	- Creates the epidemic model
