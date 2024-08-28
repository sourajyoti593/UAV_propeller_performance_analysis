UAV Propeller Performance Analysis
Project Overview
The increasing use of small Unmanned Aerial Vehicles (UAVs) in civil and military applications has brought attention to the need for optimizing propulsion systems. This project aims to address aerodynamic challenges associated with small UAVs by developing a data-driven framework to predict propeller performance, crucial for urban air mobility. The project leverages both standalone and ensemble machine learning techniques to forecast thrust coefficient, power coefficient, and efficiency based on blade geometry and operational inputs.

Objectives
Data Preparation: Combine and preprocess datasets containing propeller and blade geometry data.
Feature Engineering: Calculate essential features like radius and chord distributions, blade area, disc area, and propeller solidity.
Modeling: Develop machine learning models to predict the performance metrics of propellers.
Analysis & Visualization: Perform bivariate analysis and create visualizations, including heatmaps, to identify correlations and insights.
Datasets
The project uses multiple datasets containing experimental data and geometric characteristics of UAV propellers:

Experiment_vol1.xlsx, Experiment_vol2.xlsx, Experiment_vol3.xlsx: These files contain data on propeller performance metrics.
Geom_vol1.xlsx, Geom_vol2.xlsx, Geom_vol3.xlsx: These files include geometric properties of propellers and blades.
Each dataset contains the following key variables:

Propeller Name, Blade Name, Propeller Brand
Number of Blades, Propeller Diameter, Propeller Pitch
Advanced Ratio, RPM, Thrust Coefficient, Power Coefficient, Efficiency
Project Tasks
Week 1
SQL Analysis: Perform data analysis tasks using SQL, such as identifying high-performing propellers and calculating total propellers with specific efficiency outputs.
Data Preparation: Merge experimental datasets and address missing values.
Week 2
Feature Engineering:
Calculate blade area using radius and chord distributions.
Compute the propeller’s solidity and integrate it into the dataset.
Data Analysis:
Perform bivariate analysis and create visualizations.
Generate a heatmap to showcase correlations between variables.
Machine Learning:
Build Gradient Boosting models to predict propeller performance.
Compare models with and without missing value imputation and solidity feature.
Tableau Dashboard:
Create a Tableau dashboard to present key findings and visualizations.
Instructions
Data Preparation:

Load all datasets into the Python environment.
Rename variables to align with Python naming conventions.
Calculate required distributions and areas.
Integrate all processed data into a single dataset.
Modeling:

Develop models focusing on propellers with 2 blades.
Evaluate model performance on other propeller configurations.
Compare different modeling approaches and document findings.
Visualization:

Use Python visualization libraries and Tableau for data storytelling.
Emphasize clear, insightful representations of data relationships.
Tools and Technologies
Programming Languages: Python
Libraries: Pandas, NumPy, Matplotlib, Seaborn
Machine Learning: Scikit-learn, Gradient Boosting
Data Visualization: Tableau
Database Management: SQL
Conclusion
This project provides a comprehensive approach to UAV propeller performance analysis, from data preparation and feature engineering to model development and visualization. The results will contribute to optimizing UAV propulsion systems, enhancing performance, and supporting the growing field of urban air mobility.
