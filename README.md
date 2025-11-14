📘 Google Play Store Apps & User Reviews – Exploratory Data Analysis
📌 Project Overview

This project performs a detailed Exploratory Data Analysis (EDA) on Google Play Store app metadata and user review sentiment data. The analysis focuses on data wrangling, cleaning, preprocessing, feature exploration, visualization, and insight extraction to understand app performance trends, user behavior, and category-level patterns.

🎯 Objectives

Perform data wrangling and cleaning on Play Store data

Preprocess features such as installs, price, size, ratings, and reviews

Analyze category-wise app distributions

Explore the relationship between app ratings, installs, size, and type

Examine sentiment trends in user reviews

Build meaningful visualizations to support insights

Identify actionable patterns for app developers and business decision-makers

🗂️ Datasets
1. Play Store App Dataset

Contains key metadata:

App name

Category

Rating

Reviews

Size

Installs

Type (Free/Paid)

Price

Content Rating

Genres

Last Updated

Minimum Android Version

2. User Review Dataset

Contains:

App name

User review text

Sentiment label (Positive, Negative, Neutral)

Sentiment polarity

Sentiment subjectivity

⚠️ Dataset Note

The dataset files are not included in this repository.
Only the notebook is provided, and it contains all code required to load and process the dataset.

🧹 Data Cleaning & Preprocessing
✔ Steps Performed:

Removal of duplicate entries

Standardizing column formats and fixing inconsistent values

Cleaning numeric columns containing characters (e.g., “1,000+”, “$4.99”)

Converting datatypes:

Reviews → integer

Installs → integer

Price → float

Rating → float

Handling missing values logically

Processing “Size” column (KB, MB, “Varies with device”)

Standardizing content ratings and categories

Parsing and refining Android version compatibility

📊 Key Insights
⭐ 1. Category Distribution

Categories such as Family, Game, and Tools dominate the Play Store.

⭐ 2. Rating Trends

Most apps are rated between 4.0 and 4.5.

Paid apps tend to have slightly higher average ratings.

⭐ 3. Installs Analysis

Free apps receive significantly more installs than paid apps.

Install distribution is heavily right-skewed.

⭐ 4. Reviews vs Ratings

Highly installed apps have huge review counts, but ratings don’t always correlate with installs.

⭐ 5. App Size Patterns

Larger apps are concentrated in categories like Games and Entertainment.

⭐ 6. Price Distribution

Majority of apps are free; paid apps mostly fall under the $0.99–$4.99 range.

⭐ 7. Sentiment Analysis of User Reviews

Most user reviews are Positive, followed by Neutral, then Negative.

Some apps with high installs still show negative sentiment trends.

📈 Visualizations Included

Rating distribution

Category-wise app count

Reviews vs ratings scatter plot

Content rating distribution

Price distribution of paid apps

Sentiment polarity charts

Correlation heatmap

Boxplots for size, ratings, reviews

🛠️ Tech Stack

Language:

Python

Libraries:

Pandas

NumPy

Matplotlib

Seaborn

Plotly

Environment:

Google Colab

▶️ How to Run the Notebook

Clone or download the repository

Open the .ipynb notebook in Google Colab or Jupyter Notebook

Upload the dataset files manually 

pip install pandas numpy matplotlib seaborn plotly

Run all cells in order

🚀 Future Enhancements

Build machine learning models for rating prediction

Perform advanced NLP sentiment analysis

Create an interactive dashboard using Streamlit

Develop a recommendation system based on category and reviews

Time-series analysis on “Last Updated” information

👩‍💻 Author

Priya Shinde
Data Science Enthusiast
GitHub: add your GitHub link here
