# WiDS_2025_ADHD
Code for top 5% (#37 of 1099) submission to the Women in Data Science Datathon for 2025: "Unraveling the Mysteries of the Female Brain: Sex Patterns in ADHD", hosted on Kaggle 


# Data Structure 
Data were provided in the form of 4 tabular matrices: categorical, quanitative, connectome, and solutions. 
## Categorical 
Categorical data were derived from behavioral surveys administered to study participants. These categories related to non-numeric scales and groups such as demographics, enrollment year, study site, and parental education and occupation (Barratt Social Status). 

## Quantiative 
Quantitative data were derived from testing assessments such as color vision, handedness, age at MRI, and ADHD-related behavoral measures. 

## Connectomes 
MRI functional connectome data were provided as a vector of connection magnitudes  between 200 locations in the Schafer atlas for each participant. 

## Solutions
For the training data, solutions were provided in the form of binary sex (0=M, 1=F) and ADHD diagnosis (0=neurotypical, 1=ADHD diagnosis) variables. 

# Code
Two different types of code are provided for three different approaches used: Notebooks and python files. 
## Notebooks 
Kaggle notebooks were used to develop and train the two neural network approaches. 
### CNN 
The first neural network approach is a simple 1D convolutional neural network comprised of three layers of convolution-relu activation and three fuly connected layers with batch nromalization and dropout to counteract overfitting.  
### Transformer 
The second neural network approach uses a two-step sequence transformer.  
## Python files 
Classical or statistical machine learning solutions were developed using scikit-learn on the Spyder IDE through an Anaconda distribution. These files are very similar to those used for the [PREPARE2-Social] (https://github.com/lm-b/PREPARE_2_social) challenge.  

# Submission Results
The scikit-learn approaches performed best in ensemble. 
Approach    |      Train F1      |    Test F1        |   Final F1 
Approach    |      Train F1      |    Test F1        |   Final F1 
Approach    |      Train F1      |    Test F1        |   Final F1 
Approach    |      Train F1      |    Test F1        |   Final F1 
Approach    |      Train F1      |    Test F1        |   Final F1 
Approach    |      Train F1      |    Test F1        |   Final F1 


