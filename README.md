Open Policing Data Analysis

Introduction

The study of policing practices through statistical analysis provides crucial insights into patterns of law enforcement, social disparities, and systemic biases within society. This project leverages publicly available open policing data from the Stanford Open Policing Project to explore these issues. By analyzing factors such as race, gender, location, and the outcomes of police interactions (citations, warnings, and arrests), we aim to identify trends and potential biases in law enforcement practices across different cities.

Through the application of descriptive and inferential statistical methods, our analysis seeks to uncover significant patterns in police activity, contributing to policy discussions and efforts aimed at promoting fairness and equity in policing.

Project Overview

The primary objective of this project is to explore potential biases related to race and sex in policing practices. Specifically, we investigate:

Whether biases exist based on race (subject_race) and sex (subject_sex).

How these biases may influence the likelihood of receiving citations, warnings, or arrests.

The time periods in which these events occur.

To achieve this, we undertake the following steps:

Data Preprocessing: Cleaning and handling missing values.

Descriptive Statistics: Identifying key features and summarizing distributions.

Inferential Analysis: Performing statistical tests to draw meaningful conclusions.

Cross-City Comparison: Analyzing individual cities first and then comparing results across different locations.

Finding and Cleaning Data

The datasets used for this analysis come from cities such as San Diego, Charlotte, and Nashville. These datasets vary in size and primarily contain categorical variables, with age being the only numerical feature.

Key Challenges in Data Cleaning:

Missing Values: Addressed by focusing on features with fewer NaN values.

Duplicates & Inconsistencies: Standardized labels across datasets.

Feature Selection: Ensured that selected features were common across cities to enable fair comparison.

The primary features considered in our cross-city analysis include:

subject_sex

subject_race

subject_age

arrest_made

citation_issued

warning_issued

time_period

For more information on the dataset, visit the Open Policing Project.

Descriptive Analysis

Descriptive statistics help summarize and visualize key trends in the dataset. This phase of the analysis aims to answer the following questions:

How are traffic violations distributed across different racial and gender demographics?

What are the predominant types of traffic violations for each racial and gender group?

When and where do these violations most frequently occur (time of day, day of the week, specific areas)?

What is the average age of drivers involved in violations across demographics?

How do traffic violation rates and outcomes (warnings, citations, and arrests) compare across racial and gender groups?

Through numerical measures, tables, and visualizations, we provide a structured analysis of these trends, paving the way for deeper inferential investigations.

Usage

To run the analysis, clone this repository and execute the following steps:

# Clone the repository
git clone https://github.com/muratal49/Statistical-Analysis-on-Open-Policing.git

# Navigate to the project directory
cd open-policing-analysis

# Install required dependencies
pip install -r requirements.txt

# Run the analysis script
python analysis.py

Contributing

Contributions are welcome! Feel free to open issues, submit pull requests, or suggest improvements to enhance the analysis.

License

This project is open-source and available under the MIT License.
