This project aims to analyze shark attack incidents using a Python-based data pipeline. The goal is to explore the data through a series of steps, including data collection, cleaning, manipulation, and visualization. The analysis addresses key questions about shark attacks globally and helps provide insights for shark conservation and safety efforts. 🌍

The following steps were carried out in the project:

Data Collection/Acquisition 📥\n/n
Data Cleaning 🧹
Data Manipulation 🔄
Data Visualization (plots, tables) 📈

The aim is to:

Identify high-risk areas and activities that can be addressed to reduce shark attacks. 🚫
Prove that most shark attacks are non-fatal and unprovoked, contributing to shark conservation efforts. 🦈💙
Identify demographics that are most at risk to help inform targeted prevention campaigns. 🎯

Process Followed 🔄
1. Data Collection/Acquisition 📥
I selected the dataset from Kaggle, which contains detailed records of shark attack incidents, including:

Year of the attack 📅
Location of the attack (latitude, longitude) 🌍
Type of activity the victim was engaged in 🏄‍♂️
Outcome of the attack (fatal, non-fatal) 💀👍
Other environmental and demographic details 🌊🌞
2. Data Cleaning 🧹
Key steps taken during data cleaning:

Handling Missing Values: ❓
Removed columns with more than 70% missing values 🚮.
Replaced missing text data with 'UNKNOWN' for consistency 🔄.
Text Cleaning: ✍️
Renamed columns for clarity 📑.
Corrected inconsistent text entries 🔠.
Outlier Detection: 🔎
Removed outliers in the 'year' column by filtering out any years before 1850, as they were deemed irrelevant for analysis.
3. Data Manipulation 🔄
Key manipulations:

Created dataframes to track:
Shark attacks per year 📅
Shark attacks by region within all countries 🌍
Shark attacks by region within the top 3 countries with the most incidents 🌎
4. Data Visualization 📈
I created multiple visualizations to summarize the data and gain insights:

Line Chart: Evolution of shark attacks per year 📉.
Pie Charts:
Breakdown of fatal vs. non-fatal shark attacks 🧑‍⚖️💀.
Breakdown of unprovoked vs. provoked attacks 🦈💢.
Breakdown of attacks by gender 👩‍🦱👨‍🦰.
Bar Charts:
Ranking of activities by total shark attacks 🏄‍♂️⚖️.
Ranking of countries by number of attacks 🌎.
Top regions for shark attacks within the top 3 countries 📊.
