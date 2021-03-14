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

### Additional Information:
As mentioned earlier, we used Kaggle dataset to enrich our dataset for analysis purposes(future scope).
