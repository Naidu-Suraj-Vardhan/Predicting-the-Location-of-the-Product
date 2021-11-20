# Predicting-the-Location-of-the-Product

This is a Machine Learning Event called ```Data Analyzer Tz'21``` hosted by ```RGUKT,Nuzvid``` in a TechFest called ```Teckzite``` in ```kaggle```.
Click this [link](https://www.kaggle.com/c/data-analyzer-tz21/overview) to navigate to competition page.
## About the Data
This is a practical business case where you have to identify proper data for the products described in the below dataset. And build a model which can identify correct label associated with the description. You will have 24 unique labels mentioned by column "Primary Site Code" that are to be predicted.
Data description
#### Types of the columns :
1. Source System Code - String
2. SDQ MPN Key - String
3. Product Number - String
4. product description - String
5. Minor Code - String
6. Primary site code - String (This is the target variable)

#### Description of each columns in the dataset :
1. Source System Code - From where did the product description is generated
2. SDQ MPN Key - A unique category for multiple number products
3. Product Number - number of the product
4. product description - Description of the product
5. Minor Code - The code associated with type of product
6. Primary site code - Location of the product (This is the target variable)

In this event I've more focussed on Feature Engineering and ended up being on Top in the Event

## Installation :

1. Download this repo in a zip file by clicking this [link](https://github.com/Naidu-Suraj-Vardhan/Predicting-the-Location-of-the-Product/archive/refs/heads/main.zip) or execute this from the terminal: ```git clone https://github.com/Naidu-Suraj-Vardhan/Predicting-the-Location-of-the-Product.git ```.
2. Install the [Anaconda Environment](https://anaconda.org/anaconda/anaconda-navigator) .
3. Navigate to the repo directory and create a conda environment. Then install the dependencies with ```pip install -r requirements.txt```.
4. Run the  ```Predicting the Location of the Product.ipynb ```.

### Dependencies :

1. Numpy
2. Pandas
3. Scikit-Learn
4. Matplotlib
5. Seaborn
6. XGBoost
