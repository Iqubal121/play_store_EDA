## Google Play Store EDA
This repository contains the exploratory data analysis (EDA) of the Google Play Store dataset. The analysis focuses on uncovering insights related to app categories, ratings, pricing, reviews, and other key aspects to better understand the Play Store ecosystem.

#### Table of Contents
Overview

Dataset

Objectives

Libraries Used

Exploratory Data Analysis

Key Insights

Conclusion

How to Run

Contributing

License

### Overview
In this project, we perform an in-depth analysis of the Google Play Store dataset. By cleaning and visualizing the data, we aim to extract valuable insights into the performance of apps based on various features like app ratings, categories, pricing, reviews, and installations.

### Dataset
The dataset used for this project is available on Kaggle, which contains information about over 10,000 apps from the Play Store. The dataset includes columns such as:

1. App Name
2. Category
3. Rating
4. Reviews
5. Size
6. Installs
7. Type (Free/Paid)
8. Price
9. Content Rating
10. Genres
11. Last Updated
12. Current Version
13. Android Version

### Objectives
The primary goals of this analysis are:

To analyze the distribution of app categories.

To find the relationship between app ratings and other features (e.g., size, number of reviews).

To understand the pricing structure of apps and its impact on app ratings and installations.

To identify trends related to the number of installations for different app categories.

To derive insights that can help app developers make data-driven decisions.

### Libraries Used
The following Python libraries were used to perform the analysis:

**Pandas:** For data manipulation and cleaning.

**NumPy:** For numerical operations.

**Matplotlib:** For basic plotting and visualizations.

**Seaborn:** For advanced data visualization.

**Scikit-learn:** For handling missing data and scaling.

### Exploratory Data Analysis
The EDA process consists of the following steps:

**Data Cleaning:** Handling missing values, converting data types, and correcting anomalies (like incorrect pricing and installation numbers).

**Univariate Analysis:** Understanding the distribution of individual features like ratings, price, and size.

**Bivariate and Multivariate Analysis:** Exploring relationships between multiple features such as ratings vs. installs or price vs. app size.

**Visualization:** Creating bar plots, histograms, scatter plots, and box plots to visualize key relationships and trends.

**Insights Generation:** Summarizing key findings from the analysis.

### Key Insights
Some of the key insights discovered through this analysis include:

**Most Popular Categories:** Games and Family are the most popular categories by number of apps.

**Free vs Paid Apps:** Free apps generally have more installs compared to paid apps, but paid apps often have higher average ratings.

**Impact of Reviews on Ratings:** A pps with a higher number of reviews tend to have higher ratings.

**Pricing Strategy:** The majority of apps are free, and paid apps tend to cluster around lower price points.

### Conclusion
This project demonstrates the potential of using EDA to uncover meaningful patterns in in-app data. The insights gathered can be useful for developers, marketers, and business strategists to enhance app visibility and user engagement on the Google Play Store.

### How to Run
Clone the repository:
git clone (https://github.com/Iqubal121/play_store_EDA/blob/dddcf0ce8566c2fa9054933f2d78e643101a65fc/PlayStore_App_Review_Analysis_EDA_Projects.ipynb)

###Install the required Python libraries:

pip install -r requirements.txt

### Run the Jupyter notebook:
jupyter notebook Play_Store_EDA.ipynb
Explore the notebook to view the analysis and visualizations.

### Contributing
Feel free to contribute to this project by submitting a pull request. You can also open an issue for bug reports or feature requests.

### License
This project is licensed under the MIT License - see the LICENSE file for details.




