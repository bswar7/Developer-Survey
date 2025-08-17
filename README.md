# Developer Survey 2024 – Analysis

![4844cb87ed75ac445329a17395aa3753](https://github.com/user-attachments/assets/d260e91e-5cae-4485-9d7f-aba446ceb47c)


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

### Analysis Steps
- Data cleaning and preprocessing.
- Filtering important columns such as (AI tools, country, Employment, Education level).
- Creating visualizations using bar charts, histograms, and correlation plots.
- Extracting insights on AI usage, education, and work arrangements.

### Key Findings:

- Education: While many developers hold a bachelor’s degree, online platforms remain the most common resource for learning. JavaScript is still the most widely used programming language, though technology preferences differ.
- AI: Non-AI users tend to earn higher salaries than AI users. The USA has the highest average salary for both groups. Job satisfaction is nearly the same between AI and non-AI users.
- Work Arrangement: Hybrid work is the most common setup, while fully in-person roles are the least common. Developers in the USA earn the most across all arrangements. Clear differences exist in language and database preferences between in-person developers and those working hybrid or remote.

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


