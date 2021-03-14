### Getting Started:
This dataset provides information on ingredients, nutritional values, meal_type, max_ready time when searched by recipes.The main source of this dataset is `spoonacular.com`. We used additional dataset from Kaggle to enrich the created dataset from the `spoonacular.com`.

The sources are listed below:  
1.`https://spoonacular.com/`  
2.`https://www.kaggle.com/irkaal/foodcom-recipes-and-reviews`

### Pre-requisites:

+ Python3
+ JuypterNote Book
+ Additional Python Libraries "Schedule" - To schedule the pyhton scripts.(pip install Schedule)

### To run code snippets:

Extract the zip file and  run each cells step by step in the order how snippets arranged in the Juypter notebook to create the dataset.

***NOTE***: Schedule Job script or code in first cell alone to be execute in Pycharm or similar editors.
On executing the Schedule Job script, pass one "cuisine_type" at a time with "meal_type" and "diet_type" list values to avoid API key Access limit issue.


The output produced from API will be in JSON format and than can be converted to CSV format based on the fields/columns we required.

### Folder Information:

1.`FinalDataset` - Have the final dataset created from both the sources.  
2.`Processed Pre-datasets` - Have datasets created from API and Kaggle extraction of individual csv files. Using `dataset_api` & `dataset_kaggle_v1` datasets final `Recipes and Ingredients_V1 `dataset can be created. From `Recipes and Ingredients_V1` dataset, final dataset `Recipes and Ingredients_V2` created by appending "Meal_type" & "Max Ready Time" columns.
3.`JSON` - Have JSON files of each cuisine types with recipes information extracted from API.  
4.`csv` - Having respective csv file of each json recipes fetched from API.  
5.`Kaggle` - It have the `recipes.csv` file used for cleansing and formatted to append with the dataset created through API.  

`Group-Project-code snippets` - contains all code snippets used for preparing the dataset and arranged in sequential order for execution.  

***NOTE*** : Some files like `datasetkaggle.csv` in `Processed Pre-datasets` folder that are produced during cleansing and processing stages(Can be used for references). 

### Additional Information:
As mentioned earlier, we used Kaggle dataset to enrich our dataset for analysis purposes(future scope).
