# 🚀 Google Search Trend Analysis with pytrends


**✨ Project Overview**

This project showcases data engineering and analytical skills by utilizing the pytrends library, an unofficial Python wrapper for the Google Trends API. The core objective was to programmatically extract, analyze, and visualize global market interest for key technological terms, specifically focusing on "artificial intelligence" over the last 12 months.

This solution demonstrates proficiency in robust API interaction, data wrangling with Pandas, and generating impactful visualizations for strategic insights.


**🔬 Core Analytical Methodology**

The analysis within the Google Search Analysis.ipynb notebook follows a structured, data-driven approach:

1. Data Acquisition: Connecting to Google Trends and defining the primary search term: "artificial intelligence".

2. Geographic Interest Analysis: Utilizing the interest_by_region() method to identify and visualize the top 15 countries with the highest relative search interest for the keyword. This step uses Plotly Express to generate a visually appealing choropleth map.

3. Time-Series Trend Identification: Employing the interest_over_time() method to track the temporal popularity of "artificial intelligence" over the 12-month period, visualized using Matplotlib.

4. Competitive Trend Comparison: Conducting a simultaneous time-series analysis comparing the search interest for "artificial intelligence" against the parallel fields: "Cloud Computing," "Data Analysis," and "Machine Learning".


**🛠️ Technical Skills Demonstrated**

- API Interaction: Successfully retrieving data from an unofficial, rate-limited web API (pytrends).

- Error Handling (Rate Limiting): The code includes using time.sleep(5) to demonstrate best practices for managing Google's status code 429 (TooManyRequestsError).

- Data Wrangling: Efficiently transforming raw API JSON/CSV data into structured Pandas DataFrames for analysis.

- Data Visualization: Mastery of visualization libraries to create clear, analytical plots: matplotlib, seaborn, and plotly.express for interactive mapping.


**📊 Key Visual Output**

- Top 15 Global Hubs: A bar chart showing the highest regional interest scores for "artificial intelligence."

- Temporal Popularity: A line graph illustrating the volatility and growth of "artificial intelligence" search volume over the past year.

- Competitive Landscape: A multi-line comparison plot revealing the relative search volume trends among AI, Cloud Computing, Data Analysis, and Machine Learning.
