# Data Roles Job Market Analysis

A Python project analyzing Data jobs postings worldwide — including salary insights, job counts, top-paying roles, and geographic trends.


## Overview

This project collects, cleans, and analyzes job postings for Data Analyst, Business Analyst, Data Scientist, and similar roles from multiple countries.
It provides insights into:

- Salary distributions
- Highest‑paying and lowest‑paying roles
- Job demand by region
- Required skills and technologies
- Trends across industries
NOTE: All analysis is done using Python, Pandas, Matplotlib and Seaborn.


## Table of Contents

- Folder 1 contains: Basic Python Commands
- Folder 2 contains: Advanced Python Commands/Functions
- Folder 3 contains: the python project itself


## Features

- Clean and preprocess raw job posting data
- Extract salary ranges and compute statistics
- Identify top-paying job titles across different countries
- Visualize salary distributions
- Compare job demand across different countries
- Export results to CSV/Excel

## Exmaples
### What are the most demanded skills for the top 3 data roles?

For the code, click on this link: [Skills_Count.ipynb](3_Project\2_Skills_Count.ipynb)

### Results

![Chart with the likelyhood of a certain skill to be required for a Data job](3_Project\images\skills_count.png)

### Insights

- Python is a skill with high demand (needed for a lot of job posts), we can see that based on the chart, it shows us that in these three Roles "Analyst" with 28%, "Engineer" with 63% and "Scientist" with 71%.
- SQl as alwys comes king with a miminum 49% of the jobs requiring this basic skill
- Also we can observe a significant rise in clodu technologies such as AWS, which have become very relevant in todays world.
