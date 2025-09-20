# movies-box-office

Project Description

Developed a predictive model to estimate box office performance of movies using YouTube trailer statistics. The project involved data collection, integration, and modeling to explore the relationship between online engagement and financial success.

Scripts and Workflow
1.	YouTubeAPI_web_scraping.ipynb – Collected movie trailer statistics (views, likes, comments) via the YouTube API and exported results to Excel.
-	Input: YouTube API data
-	Output: Trailer statistics dataset (Excel)
2.	box_office_aggregation.ipynb – Cleaned and merged YouTube trailer statistics with box office data from IMDb into a consolidated dataset.
-	Input: IMDb box office data (Excel), YouTube trailer dataset
-	Output: Combined dataset with movie statistics (Excel)
3.	regression_model.ipynb – Built a regression model to predict box office revenue based on trailer engagement.
-	Input: Consolidated dataset from step 2
-	Output: Predictive regression model

Notes
•	Trailer engagement was measured by views, likes, and comments.
•	Due to strong multicollinearity among the three metrics, only number of views was used in the final model.
