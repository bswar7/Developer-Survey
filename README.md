# Developer Survey 2024 – Analysis

## Overview 

This project analyzes the [2024 Stack Overflow Developer Survey](https://survey.stackoverflow.co/2024/) to understand how different factors affect developers’ salaries, job satisfaction, and tool usage across the top 10 countries. 
For our project, we focused on three main themes shaping today’s developer experience:
First: Focused on survey reliability, company tool preferences versus developer preferences, and the most common resources developers use to learn coding.
Second: Investigated the impact of AI tools on developers’ salaries, satisfaction, and adoption across countries.
Third: Examined how work arrangements (remote, hybrid, in-person) influence job satisfaction, salary, AI adoption, and technology preferences.

The goal of this project is to provide insights into how job role, education, AI usage, and work conditions shape the professional experience of developers worldwide.


## Dataset:

- Source : [2024 Stack Overflow Developer Survey](https://survey.stackoverflow.co/2024/)
- Size: ~65,000 developer responses
- Format: CSV (stored under data/raw/)

## Analysis

- Education: While many developers hold a bachelor’s degree, online platforms remain the most common resource for learning. Preferences in technology differ, but JavaScript continues to be the most widely used programming language.

- AI: Findings indicate that non-AI users generally earn higher salaries compared to AI users. Among all countries, the USA records the highest average salary for both groups. However, job satisfaction levels appear nearly the same between AI and non-AI users.

- Work Arrangement: The majority of participants work in hybrid setups, while fully in-person roles are the least common. Across all arrangements, developers in the USA earn the most. The data also highlights noticeable differences in language and database choices between in-person developers and those working remotely or in hybrid models.

## How to Run: 
- Clone or download this project.
- Open the Jupyter Notebook (.ipynb) file.
- Run the cells step by step.
- Make sure the dataset is placed in the correct directory. 

## Dependencies: 
The Python libraries required for this project are:

- pandas → for data manipulation and analysis.
- matplotlib.pyplot → for creating visualizations and plots.
- seaborn → for advanced statistical visualizations.
- re → for working with regular expressions (text cleaning and pattern matching).
- matplotlib.ticker → for customizing ticks and formatting in plots.


