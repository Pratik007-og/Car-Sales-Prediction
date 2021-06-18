
# Car Selling Price Prediction

This project is an end-to-end project including deployment which calculates the currect selling price of a car taking into consideration various parameters or features like Fuel Type, Number of previous owners, Initial buying price, Age of the car etc.
It makes use of a regression model using RandomForestRegressor to calculate the selling price.



## Data Collection

The dataset has been downloaded from [kaggle](https://www.kaggle.com/nehalbirla/vehicle-dataset-from-cardekho).
This dataset contains information about used cars listed on www.cardekho.com
This data can be used for a lot of purposes such as price prediction to exemplify the use of linear regression in Machine Learning.

It contains three files:
1. CAR DETAILS FROM CAR DEKHO.csv
2. Car details v3.csv
3. car data.csv

The dataset used for this project is car data.csv but you are free to use whichever dataset you want to for the model.

The columns in the given dataset is as follows:

1. Car_Name
2. Year
3. Selling_Price
4. Present_Price
5. Kms_Driven
6. Fuel_Type
7. Seller_Type
8. Transmission
9. Owner

  
## Installation 

Install the required modules with the following command:

```bash 
  pip install -r requirements.txt
```
You will also need to have software installed to run and execute a Jupyter Notebook.
If you want to use jupyter Notebook, you can install it using:

Using pip:
```bash 
  pip install notebook
```
or

Using Anaconda:
```bash 
  conda install -c conda-forge notebook
```

