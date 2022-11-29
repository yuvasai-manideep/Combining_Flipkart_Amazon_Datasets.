# Combining_Flipkart_Amazon_Datasets.
Models for combining Amazon and Flipkart datasets.

## Uses:

•	To know the different products offered by the Flipkart and Amazon.

•	Compare the retail prices in both Flipkart and Amazon easily.

•	Compare the Discounts offered by the Flipkart and Amazon.

## Packages Used:

•	Pandas

•	NumPy

    To combine two Datasets, Identification of columns with Unique values is necessary. It is possible to combine Two Dataset with the columns with Unique values.
    
The datasets are taken from free open data sources. It is found that the columns “uniq_id”, “product_url”, “pid”, “description”, “product_specifications” are the columns with unique values.
Here, I mention 4 models to combine the Datasets.
	  As the first step, Load the Datasets into the jupyter notebook.
## Model-1

•	In this model, it is better that to slice the required columns from 2 Datasets First and change the column headers manually.

•	Next use the Merge function to combine both the Datasets based on one of the Column with unique values in Two Datasets i.e., “uniq_id”.

## Model-2

•	In this model, the process of slicing and renaming the column headers will be done in a function when the user Call the function.

•	The difference is, instead of combine the entire Datasets, it slices the data with “pid” column values which are related to the “product name” mentioned by the user. 

## Model-3

•	In model-3, the conditional statements were used which allow users to extract the data based on either “product name” or “product id” (pid).

•	After selecting the column, the user needs to enter the product name or product id based on selected Column.

## Model-4

•	In this model, the conditional statements were used.

•	The user had a chance to select the column on what basis the dataset needs to combine.

•	After that the user need to enter the product name for slicing the required data.

•	Condition:

    The selected column must be in the Columns with unique values in both the Datasets.

If the user selects the same product name in all the models, the output will be same.
