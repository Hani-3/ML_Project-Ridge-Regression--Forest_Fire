
# Algerian Forest Fire Prediction

This project aims to predict the Forest Fire Weather Index (FWI) in Algeria using machine learning techniques, specifically Ridge Regression. The FWI is a measure of the potential for fire growth in forests, and accurate prediction can aid in firefighting efforts and forest management strategies.


## Data

The dataset used for this project contains historical records of forest fires in Algeria, including meteorological data such as temperature, relative humidity, wind speed, rain, Fine Fuel Moisture Code, Duff Moisture Code, Drought Code, Initial Spread Index and Buildup Index. Additionally, it includes the calculated Fire Weather Index (FWI) values. The dataset is available in https://archive.ics.uci.edu/dataset/547/algerian+forest+fires+dataset
## Methodology

### Regression Model
For predicting FWI, a Ridge Regression model was chosen due to its ability to handle multicollinearity in the dataset and prevent overfitting. Ridge Regression is a regularization technique that penalizes large coefficients, thus reducing model complexity.

### Flask API
An API was developed using Flask, a micro web framework for Python. The API allows users to interact with the trained Ridge Regression model, providing predictions for FWI based on input parameters such as temperature, humidity, wind speed, and rain.
## Deployment

To deploy this project follow below steps:

1. Clone the repository
```bash
  git clone https://github.com/Hani-3/ML_Project-Forest_Fire.git
```
2. Install requirements which is already listed in requirements.txt
```bash
 pip install -r requirments.txt
```
3. Run Flask API:
```bash
python app.py
```



## Dependencies

- Python 3.x
- Flask
- scikit-learn
- pandas
- numpy
## Contributing

Contributions to this project are welcome. Feel free to open issues or submit pull requests.

