# LIAB's Instacart Kaggle Analysis

Lightning in a Bot, Inc is performing a basic analysis and prediction entry for Instacart's Kaggle Competition.

https://www.kaggle.com/c/instacart-market-basket-analysis

### Setup
##### Data
Download the Instacart data set and unzip all archived files.
 
Place all unzipped files into the /data directory, after which should contain:

    aisles.csv
    departments.csv
    orders.csv
    products.csv
    order_products__prior.csv
    order_products__train.csv
    sample_submission.csv


##### Create virutal environment
Create the virtual environment and install dependencies listed in requirements.txt.

```
$ virtualenv -p python3 env
$ source env/bin/activate
$ pip install -r requirements.txt
```

##### IPython Notebook
