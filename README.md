Capstone Project: Healthcare Data Analysis and Visualization
Welcome to the Capstone Project repository. This project focuses on analyzing and visualizing healthcare data to gain insights into patient admissions and mortality risk prediction. Using R and various data analysis techniques, this project creates an interactive dashboard to communicate these findings effectively.

Project Overview
This Capstone project is developed as part of the 'Fundamentals of Data Science in Healthcare' course. The goal is to explore and visualize data, identify trends and patterns, and, optionally, build a predictive model to forecast patient outcomes. The final dashboard, built with flexdashboard, allows users to interactively explore data across different variables and insights.

Objectives
Data Exploration: Understand the structure of the healthcare dataset, including patient demographics, types of admissions, diagnosis codes, and geographical information.
Data Visualization: Create meaningful and interactive visualizations to compare variables like age, admission type, and mortality risk.
Machine Learning (Optional): Develop a machine learning model to predict mortality risk based on patient and admission characteristics.
Dataset
The data used in this project includes hospital admissions records with variables like:

Patient Age (idade)
Type of Admission (adm_tip)
Diagnosis Code (cod_diagnostico)
Hospital ID (hosp_id)
Mortality Risk Score (mortalidade_apr31)
Admission Time (hora_admissao)
The dataset is anonymized and adheres to healthcare data protection guidelines.

Project Structure
The project is organized as follows:

/data: Contains the dataset used for analysis.
/scripts: Includes R scripts for data cleaning, exploratory analysis, and modeling.
capstone_dashboard.Rmd: The R Markdown file for creating the interactive dashboard.
output: Contains rendered HTML for the dashboard and any exported figures.
Dashboard
The dashboard is designed to provide interactive data visualizations and insights into hospital admissions and patient outcomes. Key sections include:

Patient Demographics: Visualizes age distributions and admission types.
Mortality Risk Analysis: Displays risk prediction trends based on key patient variables.
Admission Time Analysis: Uses heatmaps and other visualizations to explore patterns related to admission timing and mortality risk.
Installation and Usage
To run the project locally, you’ll need R and RStudio installed, along with the required R packages.

Prerequisites
Install the necessary R packages:

r
Copiar código
install.packages(c("ggplot2", "dplyr", "flexdashboard", "randomForest", "janitor"))
Running the Dashboard
Open capstone_dashboard.Rmd in RStudio.
Click on Knit to render the dashboard as an HTML file.
The dashboard will open in your browser for local viewing.
Publishing the Dashboard on GitHub Pages
To publish the dashboard:

Commit all project files, including the rendered HTML dashboard, to this repository.
In GitHub, go to Settings > Pages and set the source to the main branch with the root directory.
The dashboard will be accessible at the GitHub Pages link provided by GitHub.
License
This project is licensed under the MIT License - see the LICENSE file for details.
