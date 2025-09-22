MLB Batting Statistics Analysis
Project Overview: 
This project analyzes the relationship between different batting statistics for the top-performing MLB hitters in the 2024 season. Using web-scraped data from MLB.com, I conducted statistical tests and created visualizations to explore whether traditional metrics like batting average correlate with power hitting metrics like home runs.
Key Research Question
Do players with higher batting averages tend to hit more home runs, or are contact hitting and power hitting separate skills?
Data Source & Collection

Data Source: MLB.com 2024 batting statistics
Collection Method: Web scraping using Python
Dataset: Top 25 performing batters with 16 statistical categories
Key Metrics: Batting Average (AVG), Home Runs (HR), RBIs, On-base Plus Slugging (OPS), Slugging Percentage (SLG)

Technical Skills Demonstrated

Web Scraping: Automated data collection from MLB.com
Data Analysis: Python, pandas for data manipulation and cleaning
Statistical Testing: T-tests and linear regression analysis
Data Visualization: matplotlib for creating professional charts and graphs
Statistical Interpretation: Hypothesis testing and correlation analysis

Key Findings
Statistical Testing Results

T-test Analysis: Compared players above/below median batting average (.292)

High batting average group: 31.64 average home runs
Low batting average group: 24.57 average home runs
Result: p-value of 0.2061 (not statistically significant at α = 0.05)


Linear Regression: Batting Average vs OPS

R-squared: 0.267 (batting average explains only 27% of OPS variation)
Conclusion: Batting average alone is not a strong predictor of overall offensive production



Key Insights

No Strong Correlation: Higher batting average doesn't necessarily mean more home runs
Separate Skills: Contact hitting (batting average) and power hitting appear to be distinct abilities
Complex Relationships: OPS incorporates multiple factors beyond just batting average
Data-Driven Baseball: Challenges traditional assumptions about batting statistics

Visualizations Created

Home Run Leaders Bar Chart: Top 10 home run hitters in the dataset
Scatter Plot: Batting Average vs Home Runs (sized by OPS) showing the weak correlation
Correlation Matrix Heatmap: Comprehensive view of relationships between all batting statistics

Technologies Used

Python: Primary programming language
pandas: Data manipulation and analysis
matplotlib: Data visualization and chart creation
Web Scraping: Data collection from MLB.com
Statistical Libraries: For t-tests and regression analysis

Project Structure
├── Final Project Dat 301 (6).ipynb    # Main analysis notebook
├── mlb_stats_named.csv                # Cleaned dataset
└── matplotlib_hr_leaders.png          # Exported visualization
How to Run

Download the Jupyter notebook file
Ensure you have Python with pandas and matplotlib installed
Run the notebook cells sequentially to reproduce the analysis
The dataset is included as 'mlb_stats_named.csv'

Future Enhancements

Expand analysis to include more players and seasons
Investigate park factors and their impact on statistics
Add machine learning models for performance prediction
Include defensive statistics for comprehensive player evaluation


This project demonstrates proficiency in data collection, statistical analysis, and data visualization using Python.
