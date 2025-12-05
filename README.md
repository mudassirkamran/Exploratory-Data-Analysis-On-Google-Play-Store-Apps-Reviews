
![original-ab248cf8298274ac85962cee9f1d2647](https://github.com/user-attachments/assets/64be6ca7-5bb0-4b8d-9f61-53339caa731b)

# Exploratory-Data-Analysis-On-Google-Play-Store-Apps-Reviews
This project studies a large Google Play Store dataset to understand how users interact with Android apps. The work uses exploratory data analysis in Python to clean the data and find patterns in ratings, reviews, installs, size, price and app categories. A second dataset with user reviews adds deeper insight into user behaviour.

The project includes steps for data cleaning, handling missing values, converting mixed formats and removing duplicates. It also covers visual study of rating trends, install patterns, review volume, app size impact, category spread and price behaviour. The use of plots helps reveal clear links between variables. A correlation heatmap and a pairplot support the final understanding of the data.

This project gives a full walkthrough of real world EDA with useful methods for data preparation and study. It acts as a reference for new learners and a base for future work on app performance analysis.

## Problem Statement
The objective of this project is to explore and analyze the Google Play Store apps dataset, which includes information such as category, rating, size, and more. Additionally, a dataset containing customer reviews of the Android apps is provided. The goal is to discover key factors that contribute to app engagement and overall success.

##  💾 Project Files Description

<p>This Project includes :-
  <li>Google Colab NoteBook</li>
  <li>Project Summary (with the GitHub Repo link inside)</li>
  <li>Presentation PDF</li>
  <li>Technical Documentation</li>
</p>

### Data Source:
- [Dataset](https://drive.google.com/file/d/15SLvsarYG1wRaiZm21cC8XRfiWg0yTc1) - Dataset taken from AlmaBetter


## Features

- App: Name of the app on PlayStore
- Category: The category of the app
- Rating: App rating out of 5
- Reviews: Number of reviewes of the app on AppStore
- Size: The memory size needed to install the application in MB/KB/GB
- Installs: Number of user installed the app
- Type: Weather the app is Free or Paid
- Price: Price of the app of paid (0 if free)
- Content Rating: The audience for which the app is Teen/Adult/Everyone
- Genres: The genre under which the app lies
- Last Updated: When was the last time the developer pushed an update
- Current Ver: The onging version of the app
- Android Ver: The supported android version

## 🛠️ Builds with

![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)

![NumPy](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)

![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)

![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)

![Seaborn](https://img.shields.io/badge/Seaborn-blue?style=for-the-badge&logo=Seaborn)

![GoogleColab](https://img.shields.io/badge/GoogleColab-orange?style=for-the-badge&logo=GoogleColab)



## Summary and Conclusion

Google Play Store stands as one of the largest and most active Android app markets. Its wide range of apps and rich data make it a strong base for building models and spotting trends and future challenges.
In this EDA project we used two raw Kaggle datasets, one with Play Store attributes and the other with user reviews. The first dataset holds thirteen attributes and the second adds five more for deeper study.
To keep the data clean we removed duplicates and dropped fields that did not add value. The rating column held many missing values so removing them would weaken the results. We filled these gaps with the mode rating to keep the data stable.

After cleaning we carried out exploratory analysis to understand the data shape. We studied install counts in each category and checked how size, Android version and installs relate.
We also merged both dataframes to observe links between their columns. This step revealed many useful points.

Key findings include:
Reviews and installs show a positive link while price and rating show a negative one.
Art and Design holds the highest install count.
Family and Lifestyle may bring higher revenue.
Positive sentiment appears in sixty one percent of users while fifteen percent show negative views.
Free apps form ninety two percent of the data while paid apps show seven percent.
Everyone content rating covers eighty one percent of the apps.
Family, Game and Tools are the most common groups.
Game holds strong promise due to high install reach.

Tools, Entertainment, Education, Business and Medical draw many downloads.
The average rating sits at 4.17 which shows steady quality.
Users like light apps and often avoid large paid ones.
High review counts match with high installs.
Paid apps receive tougher feedback.
Installs and rating show a clear positive link.
Strong ratings need quick updates and well sized builds.
Free apps with Everyone content rating perform well.
The dataset gives strong room for business growth and wider study beyond this project.
By meeting our goals and answering the core questions we gained solid insight into the Play Store app space and the trends within it.

Connect with me on [Linkedin](https://www.linkedin.com/in/mudassir-kamran/)





