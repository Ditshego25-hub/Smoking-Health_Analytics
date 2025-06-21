# Smoking-Health_Analytics
This project is an interactive R flexdashboard built with Shiny that analyzes smoking status and its association with health indicators such as heart rate and cholesterol. Using a real dataset, it visualizes smoking prevalence, age and sex distributions, and compares cardiovascular measures between smokers and non-smokers through static and interactive plots made with ggplot2 and plotly, alongside interactive tables from the DT package. The dashboard demonstrates data cleaning, summary statistics, and dynamic reporting skills, providing clear insights relevant to public health research and data analysis.
Features

    Visualize smoking prevalence and demographics

    Compare heart rate and cholesterol levels by smoking status

    Interactive plots using plotly and ggplot2

    Data tables with sorting and filtering via DT

    Built with R, flexdashboard, and Shiny for dynamic reporting

Installation

    Install R (version 4.0 or higher) from CRAN

    Install RStudio from RStudio website

    Clone this repository or download the project files

    Install required R packages by running:

install.packages(c("flexdashboard", "tidyverse", "plotly", "DT", "shiny"))

Usage

    Open the smoking_health_dashboard.Rmd file in RStudio

    Ensure your dataset smoking_health_data_final.csv is in the correct path or update the file path in the setup chunk

    Click Run Document in RStudio to launch the interactive dashboard

    Explore the visualizations and tables to analyze smoking-related health data

Data

The dashboard uses a dataset containing demographic and clinical measurements related to smoking and cardiovascular health. Update the data path or replace the dataset as needed for your analysis.
