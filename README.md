# Housing Prediction With R

## Introduction
This is an assignment given in my DAT 611 course and it seemed rather challenging. This is a full process done with R which includes:


## Ojectives 
-> Predict the next year of US housing prices
-> Get experience with using real economic data
-> Visualize the data
-> Understand underlying assumptions about the data
-> Learn about predictive modeling using the ARIMA method

## Detailed Objectives
### 1. Data Sourcing and Loading:
Source a dataset related to a phenomenon of interest from platforms like Kaggle, data.gov, or any other reputable data repository.
Choose a dataset that aligns with your interests or research goals and download it in a format compatible with R.
Load the dataset into your R environment using appropriate functions or libraries.

### 2. Data Cleaning and Preprocessing:
Perform data cleaning to address missing values, outliers, and any inconsistencies in the dataset.
Conduct exploratory data analysis (EDA) to gain insights into the distribution of variables, relationships between features, and potential patterns or trends.

### 3. Visualization:
Create compelling visualizations to effectively communicate insights from the dataset. Utilize various plotting techniques such as scatter plots, histograms, box plots, and heatmaps to visualize relationships and distributions.
Explore advanced visualization techniques like interactive plots or geographic mapping if applicable to enhance the presentation of your findings.

### 4. Feature Engineering (if applicable):
If relevant to your analysis, generate new features or transform existing ones to improve the predictive power of your model.
Discuss the rationale behind your feature engineering decisions and their potential impact on model performance.

### 5. Machine Learning Modeling (optional):
If suitable for your chosen phenomenon and dataset, consider building a machine learning model to make predictions or classifications.
Select an appropriate algorithm, split the dataset into training and testing sets, train the model, and evaluate its performance using suitable evaluation metrics.
Fine-tune the model parameters as necessary to optimize performance.

### 6. Discussion and Conclusion:
Interpret the results of your analysis and discuss key insights regarding the phenomenon under investigation.
Reflect on the strengths and limitations of your analysis, including any challenges encountered during data preprocessing or modeling.

### 7. R Notebook Compilation:
Document your entire analysis process, including code snippets, visualizations, and textual explanations, in an R Notebook.
Ensure that your notebook is well-organized, with clear headings, comments, and markdown cells.

The discussion might be done in a power point. 

## Data
This data was sourced from S&P CoreLogic Case-Shiller 20-City Home Price Sales Pair Counts (SPCS20RPSNSA).
Link to the data here: https://fred.stlouisfed.org/series/SPCS20RPSNSA

## Note
I had to learn R on this project and these code might not be accurate and the analysis might not be exhaustive.

## Other Details
R Libraries Used: tidyverse, forecast, tseries

R Functions Used: read.csv(), ts(), auto.arima(), accuracy(), plot(), forecast(), qqnorm(), qqline(), Box.test(), log(), stl(), ggseasonplot(), rbind(), exp()
