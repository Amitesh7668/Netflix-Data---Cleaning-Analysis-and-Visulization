<h1>Netflix Data Cleaning and Visualization with SQL and Python</h1>
<h1>Overview</h1>
This project aims to analyze Netflix’s content library through data cleaning, exploratory data analysis (EDA), and visualization using SQL and Python. The goal is to derive insights into the trends and patterns in Netflix's catalog, including the types of content, release trends, and genre distributions.

<h1>Table of Contents</h1>
Project Overview Dataset Tools and Technologies Data Cleaning Exploratory Data Analysis (EDA) Key Insights Visualizations Conclusion Installation Usage

<h1>Dataset</h1>
Source: The dataset used in this project is from Netflix’s Movies and TV Shows dataset. Description: The dataset contains information about movies and TV shows available on Netflix, including columns like title, type, release_year, date_added, country, duration, and genre.

<h1>Tools and Technologies</h1>
SQL: Used for initial data cleaning and transformations. Python: Used for in-depth analysis and visualization. Pandas: Data manipulation and analysis. Matplotlib & Seaborn: Data visualization. Jupyter Notebook: To document the analysis. Power BI / Tableau: For creating an interactive dashboard to visualize the analysis.

<h1>Data Cleaning</h1>
The data cleaning process involved:

Removing rows with missing date_added values. Converting date_added to a proper datetime format. Extracting month and year from date_added for trend analysis. Handling null values in columns like country and duration.

<h1>Exploratory Data Analysis (EDA)</h1>
Key analyses performed in this project include:

Monthly Releases of Movies and TV Shows:

Analyzed the count of content added each month. Observed that December had the highest number of new releases. Yearly Releases of TV Shows:

Investigated the trend of TV show releases over the years. Found a significant increase in TV shows starting from 2015. Content Type Distribution:

Compared the proportion of Movies vs. TV Shows in the Netflix library. Found that Movies account for around 65% of the total content. Top Genres Analysis:

Identified the most common genres, with Drama and Comedy leading the list. Content Duration Analysis:

Analyzed the distribution of movie durations, with most movies falling between 90 to 120 minutes. Country-Wise Analysis:

Investigated which countries contribute the most to Netflix’s content, with the USA leading.

<h1>Key Insights</h1>
December has the highest number of new content additions, indicating a focus on holiday releases. TV Show releases have increased significantly since 2015, reflecting Netflix’s strategy to produce more original series. The USA, India, and the UK are the top contributors of content on Netflix. The platform's content is dominated by Drama and Comedy, appealing to a wide range of audiences.

<h1>Visualizations</h1>
Visualizations were created to illustrate the insights, including:

Bar Chart: Monthly Releases of Movies and TV Shows. Line Chart: Yearly Releases of TV Shows. Pie Chart: Content Type Distribution (Movies vs. TV Shows). Bar Chart: Top Genres. Histogram: Duration of Movies. Conclusion The analysis of Netflix’s data reveals key trends in content releases and distribution, which can inform future strategies for content creation and curation. By focusing on popular genres and expanding TV show offerings, Netflix continues to attract a diverse audience.
