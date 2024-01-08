
firs name      father name      id
Hailemichael   Adisu            0210/12

debre berhan university
collage of computing
software engineering department
big data indivdual assignment


# Electric Vehicle Data Analysis

This repository contains code for analyzing and visualizing electric vehicle population data. The analysis includes exploratory data analysis (EDA), visualization of the dataset, and the implementation of a logistic regression model for predictive analysis.

## Dataset

The dataset used in this analysis is sourced from an Excel file named "Electric_Vehicle_Population_Data.xlsx." It includes information about electric vehicles, their model years, electric utility usage, legislative districts, and other relevant features.

## Prerequisites

Make sure you have the following Python libraries installed:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install them using the following command:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
git clone https://github.com/haile/electric-vehicle-analysis.git
cd electric-vehicle-analysis
python analyze_electric_vehicle_data.py
Visualizations
Several visualizations are generated using matplotlib and seaborn, including pair plots, histograms, count plots, and box plots. These visualizations provide insights into the distribution of data, relationships between variables, and more.

Logistic Regression Model
The code includes the implementation of a logistic regression model using scikit-learn. Categorical variables are converted to dummy/indicator variables, missing values are imputed with the mean, and the dataset is split into training and testing sets.

To run the logistic regression model, execute the following steps:

Convert categorical variables to dummy variables.
Impute missing values with the mean.
Split the data into training and testing sets.
Initialize the logistic regression model.
Fit the model to the training data.
Make predictions on the testing data.
Evaluate the model's accuracy and generate a classification report.
Results
After running the logistic regression model, the script prints the accuracy and a classification report, providing insights into the model's performance.



# AAQOL Survey Analysis

This repository contains Python code for analyzing the AAQOL survey data. The analysis involves reading an Excel file, exploring the dataset, and visualizing responses to specific survey questions.

## Dataset

The dataset used in this analysis is sourced from an Excel file named "AAQOL.xlsx." It includes responses to various survey questions related to participant demographics and their sources of survey awareness.

## Prerequisites

Make sure you have the following Python libraries installed:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install them using the following command:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
git clone https://github.com/haile/aaqol-survey-analysis.git
cd aaqol-survey-analysis
python analyze_aaqol_survey.py
The script reads the "AAQOL.xlsx" file, performs exploratory data analysis, and generates visualizations related to specific survey questions.

Visualizations
Question and Answer Distribution
The script converts the 'Q1 How did you hear about this survey?' column to string and plots a histogram to visualize the distribution of responses.
Question Bank Distribution
Visualize the distribution of responses for the question 'Q2 What is your age? (Please enter numerical number) - Open-Ended Response.'
Relationship between Gender and Survey Source
Explore the relationship between gender ('Q3 What is your gender? (Please choose one)') and the source of survey awareness.
Distribution of Gender Responses
Visualize the distribution of responses for the question 'Q3 What is your gender? (Please choose one).'

# Appointment Dataset Analysis

This repository contains Python code for analyzing appointment data. The analysis includes reading a CSV file, exploring the dataset, and visualizing various aspects of the appointment records.

## Dataset

The dataset used in this analysis is sourced from a CSV file named "appointment.csv" with Latin-1 encoding. It includes information about appointments, including features such as 'No-show', 'Scholarship', and 'ScheduledDay'.

## Prerequisites

Make sure you have the following Python libraries installed:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install them using the following command:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

git clone https://github.com/haile/appointment-analysis.git
cd appointment-analysis
python analyze_appointment_data.py
The script reads the "appointment.csv" file with Latin-1 encoding, performs exploratory data analysis, and generates visualizations related to appointment records.
Distribution of No-show
Visualize the distribution of the target variable 'No-show'.
Visualizations
Pair Plot
Relationship between Scholarship and No-show
Explore the relationship between the 'Scholarship' feature and 'No-show'.
ScheduledDay Distribution Over Time
Visualize the distribution of 'ScheduledDay' over time.
Missing Values and Summary Statistics
Feel free to customize and extend the code for your specific needs.
