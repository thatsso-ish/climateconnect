# Climate Connect
connecting the dots between climate change, agriculture, and sustainability, and providing insights to help stakeholders make informed decisions.

![](https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=Python&logoColor=white)

<div id="main image" align="center">
  <img src="https://github.com/marcmarais/2401FTDS_Regression_Project/blob/main/agri_image.png" width="450" height="300" alt=""/>
</div>

## Table of contents
* [1. Project Overview](#project-description)
* [2. Packages](#packages)
* [3. Dataset](#dataset)
* [4. Visuals](#visuals)
* [5. Modeling](#model)
* [6. Conclusion](#conclusion)
* [7. Team Members](#team-members)

## 1. Project Overview <a class="anchor" id="project-description"></a>

## 1.1 Introduction
This project aims to understand the impact of agricultural activities on climate change and develop strategies for sustainable practices. The project uses data from the Food and Agriculture Organization (FAO) and the Intergovernmental Panel on Climate Change (IPCC) to analyze CO2 emissions in the agri-food sector and predict temperature variations.

## 1.2. Objectives
* Analyze and understand the sources of CO2 emissions in the agri-food sector.
* Develop a predictive model using regression analysis to forecast temperature variations based on various emission sources.
* Identify the most significant contributors to CO2 emissions and develop strategies for reducing these emissions.
* Provide actionable insights for stakeholders in the agri-food sector, including policymakers, agricultural businesses, and environmental organizations.
* Contribute to the ongoing efforts to promote sustainability within the agri-food sector by offering valuable insights and recommendations.

## 2. Importing Packages <a class="anchor" id="packages"></a>
* For data manipulation and analysis, `Pandas` and `Numpy`.
* For data visualization, `Matplotlib` and `Seaborn`.

## 3. Loading and Cleaning <a class="anchor" id="dataset"></a>

## 3.1 Data
The project uses data from the FAO and IPCC, which includes information on CO2 emissions, temperature variations, and various factors contributing to these emissions. The data is loaded into a pandas DataFrame using the read_csv function.
## 3.2 Preprocessing
The data is preprocessed by checking for null values, removing duplicates, and filling missing values with median values. The data is also normalized using the StandardScaler function from scikit-learn.
 
## 4. Visuals <a class="anchor" id="visuals"></a>
The project includes various visualizations to help understand the data and model performance:
* Correlation heatmap
* Line plot of total emissions by year
* Bar plot of average values of factors contributing to total emissions by year
* Distribution of total emissions
* Scatter plot of total emissions vs. average temperature

## 5. Modeling <a class="anchor" id="model"></a>

## 5.1 Types of models
The project uses three different machine learning models to predict temperature variations based on various emission sources:
* Linear Regression
* Decision Tree Regression
* Random Forest Regression
+ Each model is trained using the preprocessed data and evaluated using mean squared error (MSE), mean absolute error (MAE), and R-squared.

### 5.2 Model Evaluation
The performance of each model is evaluated using metrics such as MSE, MAE, and R-squared. The results are printed to the console for each model.

## 5.3 Model Saving and Loading
The trained models are saved to files using the pickle module, and can be loaded back into the project using the same module.

## 6. Conclusion<a class="anchor" id="conclusion"></a>
This project provides a comprehensive analysis of CO2 emissions in the agri-food sector, predicts temperature variations based on various emission sources, and offers actionable insights for stakeholders. The project also demonstrates the use of machine learning models to predict temperature variations and evaluates their performance using various metrics.

## 7. Team Members<a class="anchor" id="team-members"></a>

| Name                                                                                        |  Email              
|---------------------------------------------------------------------------------------------|---------------------------------            
| [Ishmael Ngobeni](https://github.com/thatsso-ish)                                           | ismaelkatlego0@gmail.com
| [Ntandoyenkosi Biyela](https://github.com/Yenkosintando)                                    | biyelantandoyenkosi12@gmail.com
| [Sharon Ramapuputla](https://github.com/Sharonramapuputla)                                  | sharonramapuputla24@gmail.com
| [Karabo Mathibela](https://github.com/karabomathibela)                                      | karabomathibela44@gmail.com
| [Pfarelo Ramunasi](https://github.com/PfareloRamunasi)                                      | pfareloramunasi@gmail.com
| [Mmakhutjo Lehutjo](https://github.com/makhutso98)                                          | makhutjolehutjo8@gmail.com
