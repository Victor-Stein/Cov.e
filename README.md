# Cov.e
Cov.e project (new seperate repo)


This project aims at predicting analysing COVID-19 Data and predict the evolution of the number of cases and deaths. The project is divided into 4 main phases:
1) Data selection 
2) Exploratory Analysis & Preprocessing
3) Predictive ML Modeling
4) Testing

Using the Jupyter Notebook file, we can analyze and visualize COVID-19 data opendata on different levels: city, state, county, region and/or continent levels. Then design visualisations to help interpret the data and learn more about the potential spread of the virus. A crucial step is to provide an effective ML model that would enable accurate prediction of the number of cases and deaths.

In this work the data is analysed from a timeseries perspective. For simplicity and analytics reasons some initial hypotheses have been made; for instance the preprocessed data take into account only Europe. Several critera have been set for the choice of the different models tested (including but not limited to: relevence to the nature of the problem, performance, ease of implementation). 

The jupyter notbook covers:

- Libraries import
- Reading the files
- Exploratory Data Analysis & Preprocessing
- Data Visualisation
- Timeseries tests
- Decomposition & Correlation tests
- Predictive ML Modeling
- Models Improvements 

This project has its limitations as the main goal is to set a framework for analysing data in general and provide an easy to understand structure than can be applicable and used to solve similar problems.
The most notable limitations are:
- The prediction variables are only the historical data of cases and deaths. ()
- Potential data logging errors related to reporting have not been aborded. (Double checking and any verifications are not feasible at least when considering the scope and scale of this project)
- Predictition results could be optimised further by setting manually certain parameters or using other methods.



DISCLAIMER: The project is for learning purposes, it IS NOT meant to provide scientific proof nor constitutes a viable analyses of the virus behaviour. 
All the data used is only valid for the first 2 quarters of 2021 at the time of file creation. Dataset used may be out of date at a certain point of time for several reasons (possible corrections being made, changes in reporting methods,etc...).
