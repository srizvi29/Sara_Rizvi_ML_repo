# 📌 Simplifying Solar Energy Production Analysis Using Machine Learning


The goal of this project is to simplify the method to calculate energy production using machine learning while taking into account various weather factors and the orientation of the panel. Likewise, this project aims to analyze various models and investigate the most suitable model.

---
## Dataset

Data is derived from the National Solar Radiation Database. It is processed through the PVLIB based energy estimate code.
Data is in 4 categories: south, east, west, and combined

# Model/method preview
Four models are implemented: SVR, RF, LSTM, ANN
Features: POA, Temperature, Wind Speed, Azimuth, Hour
Target: Energy

## Running Code
The data folder stores all the data for the 2022 and 2023 weather for Albany, NY
The notebook folder stores the EDA and Train&Testing files
The Results folder has each model separated each containing the combined and individual dataset results.

Use either the mounted google drive or downloded files to run the individual code. To transfer to colab, type "colab.research.google.com/github" in url to access file in colab

# Summary of results
 Four models were analyzed in this study: Support Vector Regression, Random Forest, Long-Short Term Memory, and Artificial Neural Network. Mean squared error and R-squared were used to evaluate the performance of the models. For the 2022 data, it was found that RF outperformed the other models in most datasets, except for south where ANN excelled. SVR generally performed poorly on most datasets. When the models were tested on the 2023 dataset, all models performed well, except LSTM. Overall, this machine learning model enables people to observe the relationship between energy and various factors in terms of vertically installed solar panels. This study will provide a simple model that can be implemented to better understand vertical building integrated photovoltaic systems.

