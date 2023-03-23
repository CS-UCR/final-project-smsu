# Final-project-smsu
Created by: Sathya Rajesh, Mohamed Abuelreich, Shaan Malhotra, Uzair Memon
### Description of the Project

This project is based around a dataset that looks at stroke victims, and other factors that may or may not contribute to a person having a stroke. The dataset has over 5000 entries, and tracks data points such as age, gender, smoking status, BMI, marital status, and other various factors, as well as whether or not the person has had a stroke

Exploratory data analysis has been done on this dataset, to see the distribution of important variables, as well as show the correlation between those variables and having a stroke.

Since this is medical data, the data has been cleaned up and there aren't many identifying factors with which you could identify an individual. As a result, this dataset did not really need a large amount of added noise to improve privacy for the people involved in the creation of the dataset

Our project is actually a hybrid of the two options that we were given. We decided to do a literature review focusing on the intersection between medical data and machine learning while also building our own predictor models. In one of the research articles we reviewed (“Predicting Stroke from Electronic Health Records” by Suri et al.) they created three predictor models (neural network, random forest, and decision tree). We decided to compare the accuracy and bias between these 3 models and two models we created (KNN and random forest).   

### Summary of Files: 

Aequitas: includes the juypter notebook with the code for the Aequitas generations, the summary of the Aequitas web tool, the three datasets from the research article models that were reformatted to fit the Aequitas model, and the citation for our use of the Aequitas tool

Literature Review: contains the literature review written for the 3 research papers and the works cited page for all three

Our Models: contains the juypter notebooks with the code for the KNN model and random forest model that we created. 

Recreating Article Code: the rmd file with the recreated code for the 3 models from the research article

Presentation Slides: a pdf version of the slides that we presented in class

EDA: visualizations for our dataset

healthcare-dataset-stroke-data.csv: our dataset



### How to run the code 
In order to run the code that is provided in the JupyterNotebooks, no additional libraries or dependancies are required. Running the code will install all required libraries by itself, without any extra effort needed from the person running the code.

