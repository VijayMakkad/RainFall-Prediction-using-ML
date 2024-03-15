**Rainfall Prediction using Logistic Regression**

This repository contains code for predicting rainfall using logistic regression. The main file is an IPython Notebook named `LogisticRegression_RainFall_Prediction.ipynb`. Additionally, it includes a pre-trained model saved as a joblib file named `aussie_rain`, and the dataset used for training and testing the model named `weatherAUS.csv`.

### Files Included:

1. `LogisticRegression_RainFall_Prediction.ipynb`: 
   - This IPython Notebook contains the code for data preprocessing, model training, evaluation, and prediction using logistic regression for rainfall prediction.

2. `aussie_rain.joblib`:
   - This file contains a pre-trained logistic regression model for predicting rainfall. It can be loaded using joblib library in Python for direct use in applications without retraining.

3. `weatherAUS.csv`:
   - This CSV file contains the dataset used for training and testing the logistic regression model. It includes various weather-related features along with the target variable indicating whether it rained the next day or not.

### Dependencies:
- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- scikit-learn

### Usage:
1. Clone the repository:
   ```
   git clone https://github.com/VijayMakkad/RainFall-Prediction-using-ML.git
   ```

2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Open and run the `LogisticRegression_RainFall_Prediction.ipynb` notebook in Jupyter environment. This notebook guides through the entire process of rainfall prediction using logistic regression.

4. To directly use the pre-trained model, load `aussie_rain.joblib` file in your Python code using joblib library:
   ```python
   import joblib

   # Load the pre-trained model
   model = joblib.load('aussie_rain.joblib')

   # Use the model for prediction
   prediction = model.predict(test_data)
   ```

### Dataset:
The `weatherAUS.csv` dataset is sourced from [Australian Weather Data](https://www.kaggle.com/jsphyg/weather-dataset-rattle-package) available on Kaggle. It contains weather-related features collected from various weather stations across Australia.

### Acknowledgments:
- This project is developed for educational purposes and inspired by real-world applications of machine learning in weather prediction.
- The dataset used in this project is sourced from Kaggle and provided by Joe Young.

### Contributors:
- [Vijay Makkad](https://github.com/VijayMakkad)

### License:
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
