Play Store Data Analysis using PySpark

This project analyzes data from the Google Play Store using PySpark, SQL for big data processing. The dataset used in this project is the googleplaystore.csv, which contains information about various apps available on the Google Play Store.

Overview

The main goal of this project is to perform exploratory data analysis (EDA) on the Play Store dataset to gain insights into the types of apps available, their ratings, categories, and other relevant information. This analysis is done using PySpark to efficiently process large-scale data.

Dataset

The dataset used in this project, googleplaystore.csv, is available in the data directory. It contains the following columns:

App: Name of the app
Category: Category to which the app belongs
Rating: Overall user rating of the app (out of 5)
Reviews: Number of user reviews for the app
Size: Size of the app
Installs: Number of user downloads/installs
Type: Paid or Free
Price: Price of the app (if paid)
Content Rating: Age group the app is targeted at
Genres: Genre(s) of the app
Last Updated: Date when the app was last updated
Current Ver: Current version of the app
Android Ver: Minimum required Android version
Analysis
The analysis includes the following steps:

Loading the dataset into a PySpark DataFrame.
Data preprocessing and cleaning (handling missing values, data type conversions, etc.).
Exploratory data analysis (EDA) to understand the distribution and characteristics of the data.
Visualizations to illustrate key findings and insights.
Statistical analysis to derive meaningful conclusions.
Requirements
Python 3.x
PySpark
SQL
Jupyter Notebook (optional, for interactive analysis)
Usage


Results
The results of the analysis are documented in the Jupyter Notebook play_store_analysis.ipynb. Key findings, visualizations, and conclusions are presented within the notebook.

Contribution
Contributions to improve the analysis or add new features are welcome! Feel free to open an issue or submit a pull request.

License
This project is licensed under the MIT License.
