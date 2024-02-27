# Predicting Rice Yields in Vietnam using Satellite Data

## 🌾 Project Overview
<p align="justify"> This project aims to develop a regression model for predicting rice yield in Vietnam leveraging satellite data. With rice serving as a staple food for over four billion people and a crucial source of livelihood for a significant portion of the global population, addressing the decline in available land and yield growth rates is paramount. Solutions focused on rice production scalability have the potential to transform global food security. </p>


### Project Objectives
- Develop a regression model for predicting rice yield using satellite data.
- Connect to public-facing data sources on Microsoft's Planetary Computer.
- Generate a preliminary R2 score using an example Jupyter notebook.
- Produce a .csv file output for upload to the challenge platform.

## 🛠️ Methodology

### Data Collection
- Obtain rice yield data from Chau Thanh, Thoai Son, and Chau Phu regions of Vietnam from a public dataset.
- Access satellite data, including spectral bands, from the Microsoft Planetary Computer portal.

### Data Preprocessing
- Preprocess rice yield data to remove missing values and outliers.
- Preprocess satellite data to eliminate noisy data and normalize it.

### Feature Engineering
- Generate various vegetation indices such as NDVI, EVI, and SAVI using satellite data as features.
- Create bounding boxes of different sizes around given latitude and longitude positions.

### Model Selection
- Experiment with several regression algorithms including Linear Regression, Random Forest Regression, and Gradient Boosting Regression.
- Select the best performing algorithm based on the R2 score.

### Hyperparameter Tuning
- Fine-tune the hyperparameters of the selected algorithm using Grid Search and Random Search methods.
- Select the best hyperparameters based on the R2 score.

### Model Evaluation
- Evaluate the final model using the test dataset.
- Assess performance using metrics such as R2 score, Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).

## 📊 Conclusion
<p align="justify"> In conclusion, this project successfully developed a regression model for predicting rice yield in Vietnam utilizing satellite data. With a high R2 score and robust performance on the test dataset, the model demonstrates potential applicability beyond the Chau Thanh, Thoai Son, and Chau Phu regions. Future extensions could involve predicting rice yield in other Vietnamese regions and potentially extending the model to forecast yields for different crops and regions worldwide. </p>

## ✍️ Authors <a name = "authors"></a>
- [@VishnuAmit](https://github.com/VishnuAmit) 
- [@roshangeorge97](https://github.com/roshangeorge97)
- [@AkileshRaoS](https://github.com/AkileshRaoS)

