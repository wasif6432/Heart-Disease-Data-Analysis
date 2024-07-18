## Heart-Disease-Data-Analysis
This repository contains a Python script for analyzing and visualizing heart disease data. The dataset includes various medical attributes of patients, which are used to predict the presence or absence of heart disease. The analysis focuses on extracting and visualizing heart disease rates based on different attributes such as age, gender, and other medical conditions.  
#
### Dataset
The dataset includes the following attributes:

- age
- sex
- chest pain type (4 values)
     - 0: typical angina
     - 1: atypical angina
     - 2: non-anginal pain
     - 3: asymptomatic
- restbps: resting blood pressure (in mm/Hg on admission to the hospital)
- chol: serum cholesterol (in mg/dl)
- fbs: fasting blood sugar > 120mg/dl 
     - 1: ture
     - 0: false
- restecg: resting electrocardiographic results
     - 0: normal
     - 1: having ST-T wave abnormality( T wave inversions and/or ST elevation or depression of > 0.05 mV)
     - 2:  showing probable or definite left ventricular hypertrophy by Estes' criteria
- thalach: maximum heart rate achieved
- exang: exercise induced angina
     - 1: yes
     - 0: no
- oldpeak: ST depression induced by exercise relative to rest
- slope: the slope of the peak exercise ST segment
     - 1: upsloping
     - 2: flat
     - 3: downsloping
- ca: number of major vessels (0-3) coloured by flouroscopy
- thal: 
     - 0: normal
     - 1: fixed defect
     - 2: reversible defect
     - 3: reversible defect
- target: 
     - 0: less chance of heart attack
     - 1: more chance of heart attack
 #
## Analysis
### Goals
Extract heart disease rates by gender and age.
Visualize heart disease rates.  
#
### Steps
### 1.) Data Preprocessing:

  - Convert numerical categorical values to descriptive categorical values for better readability.
  - Drop unnecessary columns for specific visualizations.  
### 2.) Visualization:

  - Plot heart disease rates by gender using a bar plot.
  - Plot heart disease rates by age using a bar plot.
  - Plot overall heart disease rates using a bar plot.
#
### Code
The main analysis is done in a Python script. Here is a brief overview of the script:

  - Data Loading: Load the dataset from a CSV file.
  - Data Transformation: Transform categorical numerical values to descriptive labels.
  - Visualization: Create bar plots to visualize heart disease rates based on different attributes.
#
### Dependencies
  - pandas
  - matplotlib
  - seaborn
# 
### Conclusion
This analysis helps in understanding the distribution of heart disease among different genders and age groups. The visualizations provide a clear insight into the heart disease rates, which can be useful for medical professionals and researchers.
#
Feel free to contribute to this project by opening issues or submitting pull requests.
