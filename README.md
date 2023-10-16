# data_visualization_challenge
Challenge 5
This repository contains Python code that collects, merges, and analyzes two datasets: mouse metadata and study results. The objective is to provide a comprehensive representation of findings related to the impact of different drug regimens on mice with SCC (Squamous Cell Carcinoma) tumors.

Data Collection and Merging:

Mouse Metadata: The code collects information about 249 mice, including their unique IDs, gender, age, and weight.
Study Results: It also acquires data on the development and measurement of tumor volume over a 45-day period, capturing details on timepoints, drug regimens, and the number of metastatic sites.
The two datasets are merged to create a comprehensive dataset that forms the basis for all subsequent analyses.

Data Filtering and Visualization:

Drug Regimen Analysis: The code filters the data by drug regimen and employs bar charts to visually represent the relationship between timepoints and various drug regimens. This provides insights into the effects of different treatments over time.
Gender Distribution: The gender distribution among the mice is represented using a pie chart, providing a clear overview of the balance between male and female subjects.
Statistical Analysis:

Data Distribution: The code calculates the data distribution for each drug regimen, highlighting variations among the regimens using box plots. This information helps identify trends and variations in the effectiveness of treatments.
Correlation Analysis: A scatter plot is used to illustrate the correlation between the weight of the mice and the treatment results. The code also performs a regression analysis to quantify this relationship, allowing for deeper insights into the impact of mouse weight on tumor volume.
This code utilizes information provided in class, support documentation from multiple sources on the internet, and an iterative process of trial and error.
