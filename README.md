MICROSOFT_MOVIE _ANALYSIS


Author: DAPHINE LUCAS


Overview

Microsoft has opted to establish a new film studio and seeks deeper insights into the most successful film genres at the box office. This endeavor employs descriptive statistical analysis utilizing data sourced from the IMDb website. The objective is to discern which amalgamation of genres resonates most with audiences across various metrics. To accomplish this, four distinct datasets were utilized, focusing on domestic and foreign gross sales, average ratings, number of votes, and production budgets in relation to gross revenue. The analysis identified the top-performing genre combinations in each category. Notably, the combination of Action, Adventure, and Sci-Fi emerged as the predominant choice across domestic sales, foreign sales, and number of votes, with Adventure featuring prominently in the top 20 across all three categories. Based on these findings, the recommendation for Microsoft's movie production endeavors would be to prioritize films in the Action, Adventure, and Sci-Fi genres, considering their prevalence and success within the dataset, which comprised 322 unique genre combinations post-cleaning. Additionally, Adventure and Action paired with either Animation or Fantasy are deemed viable options, given their demonstrated success. Furthermore, the combination of Adventure, Animation, and Comedy showed promising performance in both domestic and foreign sales, making it a compelling third recommendation. Adventure emerges as a consistent and robust genre choice for producing popular and successful movies.

Business problem


Microsoft aims to produce profitable movies and seeks to understand which genres are most successful in achieving this objective. To address this inquiry, an analysis of domestic and foreign sales data, as well as the production budget relative to domestic and worldwide gross, was conducted. This analysis aimed to identify the genres that yield the highest financial returns. Additionally, the average rating and number of votes for each genre were examined to gauge the correlation between popularity and financial success.

Questions to use while analyzing the data sets

What are the most voted movies and highly rated movie types?

What movie types have the highest average domestic gross and foreign gross income?

What specific metrics are considered when defining the success of a film genre at the box office?(domestic gross sale,foreign gross sales, worldwide gross sales, production budget, average rating, number of votes, genre specific metrics, rankings)

How do production budgets correlate with gross revenue for different genres, and what implications does this have for investment decisions?

What factors must be considered when determining the ideal combination of genres for Microsoft's film production initiatives?

Data sets used:
bom.movie_gross

imdb.title.basics

imdb.title.ratings

tn.movie_budgets


Repository Structure


├── README.md                           <- The top-level README for reviewers of this project

├── dsc-phase1-project-template.ipynb   <- Narrative documentation of analysis in Jupyter notebook

├── DS_Project_Presentation.pdf         <- PDF version of project presentation
