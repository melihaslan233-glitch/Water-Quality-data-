1) Project Name

Analysing Water Potability to Support SDG 6 Clean Water and Sanitation & SDG 3 Good Health and Wellbeing


2) Overview

  Access to safe drinking water remains one of the most critical global challenges. According to the United Nations Sustainable Development Goals, ensuring access to clean water and sanitation for all is essential for sustainable development. Poor water quality can lead to serious health risks and environmental problems, making effective monitoring and prediction of water safety increasingly important. Our project aims to analyse water quality data and explore how artificial intelligence techniques can be used to predict whether water is safe for human consumption. By leveraging machine learning models and exploratory data analysis, we aim to identify relationships between chemical properties of water and its potability. The dataset used in this project includes several physical and chemical parameters such as pH, hardness, dissolved solids, turbidity, and chemical compounds present in water samples. These features will be analysed to determine how they influence water potability. Through exploratory data analysis,we aim to uncover patterns and correlations between different water quality parameters and the potability of water. The results of this project can help policymakers, environmental scientists, and water management authorities in improving water quality monitoring and developing intelligent systems that detect unsafe water conditions more efficiently.

3) Background

  Clean drinking water is essential for human health, agriculture, and environmental sustainability. However, many regions around the world still face challenges related to water contamination caused by industrial pollution and inadequate water treatment systems. Water quality is determined by several chemical and physical factors. Parameters such as pH level, turbidity, dissolved solids, and chemical concentrations directly influence whether water is safe for consumption. Monitoring these parameters traditionally requires laboratory testing and manual evaluation, which can be time consuming. With the advancement of artificial intelligence and data science, machine learning techniques have become increasingly useful for analysing environmental datasets. These techniques can detect complex patterns in data and provide predictive insights that support decision making. By applying machine learning methods to water quality data, it becomes possible to develop predictive models that classify water as potable or non-potable. Such systems could help automate water quality monitoring and improve the efficiency of environmental management systems.








4) Key Objectives / Business Objectives

a) Research Questions

Which water quality parameters have the strongest influence on water potability?

How are different chemical properties of water related to each other?

Are there significant differences between potable and non-potable water samples?

Can machine learning techniques be used to accurately predict water potability?

How can data-driven approaches support sustainable water quality monitoring systems?

b) Key Steps

Collect and analyse the water potability dataset.

Perform data cleaning and preprocessing to handle missing values.

Conduct exploratory data analysis to identify patterns and relationships.

Visualize key trends using statistical and graphical methods.

Apply machine learning models to predict water potability.

Evaluate model performance using appropriate metrics.

Interpret results and assess their implications for sustainable water management.



5) Methods and Workflow

a) Datasets

The dataset used in this project is the Water Potability Dataset, which contains water quality measurements and labels indicating whether the water is safe to drink.

Dataset source: https://www.kaggle.com/datasets/adityakadiwal/water-potability

The dataset includes 3,276 water samples and the following variables: pH, Hardness, Solids, Chloramines, Sulfate, Conductivity, Organic Carbon, Trihalomethanes, Turbidity, Potability (target variable)



b) Data Cleaning and Preprocessing

Loading the dataset using Python and the Pandas library.

Identify missing values in variables such as pH, Sulfate, and Trihalomethanes.

Replace missing values using median imputation to preserve data distribution.

Standardise or normalise numerical variables if necessary.

Verify data consistency and prepare the dataset for analysis.


c) Modelling

Perform exploratory data analysis to understand the distribution of variables.

Generate correlation matrices to analyze relationships between water quality parameters.

Use visualization techniques such as histograms, boxplots, and heatmaps to identify patterns.

Apply machine learning models such as Logistic Regression, Decision Trees, or Random Forest to predict water potability.

Train and validate models using training and testing datasets.

Evaluate the models using metrics such as accuracy, precision, and recall.

d) Deliverables

Exploratory Data Analysis report describing key insights from the dataset.

Data visualizations illustrating patterns in water quality parameters.

A machine learning model capable of predicting water potability.

A final project report explaining methodology, analysis, and results.
