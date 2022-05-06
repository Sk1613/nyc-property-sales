# NYC Sales Price Prediction

**Aim:** To estimate the sales price with different information such as the age of the building, size and location.

   - For this purpose, I will clear the data.
   - Then I will make the data ready for the model with preprocessing steps. 
   - In order to understand whether this data can solve this problem, I will set up a base model with MVP quality.
   - And the results will guide the next development steps.


**About Data:**

The dataset includes information about buildings sold in NYC, such as location and price.

- SALE_PRICE: our target variable, the sale price of the property.

- BOROUGH: County code

    1- Manhattan
    2- Bronx
    3- Brooklyn
    4- Queens
    5- Staten Island

- Block & LOT: The combination of borough, block, and lot forms a unique key.

- BUILDING CLASS AT PRESENT and BUILDING CLASS AT TIME OF SALE: The type of building at various points in time.

The dataset can be accessed here: https://www.kaggle.com/datasets/new-york-city/nyc-property-sales

Files: 

  - src: 
    - nyc1-eda.ipynb: Notebook where data is analyzed
    - nyc2-model.ipynb: Notebook on which model experiments were made
    - nyc3-sql-queries.ipynb: Notebook where SQL queries are saved

   - requirements.txt


Made by sengulkaraderili@gmail.com
