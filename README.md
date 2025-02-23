# Journalism School Cost vs. US Median Income for Journalists

This project aims to analyze the cost of journalism programs, specifically at Columbia University's MS Journalism program, in relation to the median annual income for journalists in the U.S. The goal is to understand how the high costs of journalism education compare to potential earnings in the field, and whether the investment in a prestigious program like Columbia's Journalism School is justified by the financial payoff.

## Overview
In this project, I scraped data from Columbia University's MS Journalism program webpages using BeautifulSoup to extract tuition and program cost information. Additionally, I analyzed median income data for journalists from the U.S. Bureau of Labor Statistics using Pandas. The analysis provides insights into the financial challenges faced by journalism students and offers a data-driven look at the return on investment for pursuing a career in journalism.

## Key Steps and Tools
### 1. Data Collection
- **Web Scraping**: The tuition and cost data for the Columbia MS Journalism program were gathered by scraping relevant information from Columbia University's official program pages using **BeautifulSoup**.
- **US Bureau of Labor Statistics**: The median annual income for journalists was obtained from the U.S. Bureau of Labor Statistics (BLS) and analyzed using **Pandas**.

### 2. Data Analysis
- The scraped data, along with the BLS data, were combined and analyzed using Python's **Pandas** library to explore trends and relationships between journalism education costs and the median salary for journalists in the U.S.

### 3. Data Visualization
- **ggplot2 & Tidyverse**: Data visualizations were created using the **ggplot2** package in R to present the findings. Various plots such as bar charts and line graphs were employed to show the differences in journalism education costs and salary data.
- **Datawrapper**: Additional visualizations were created using **Datawrapper** for easy, interactive charts.

### 4. Images
- **Pexels**: The images used in the project, including visuals for presentations and blog posts, were sourced from **Pexels**, offering high-quality and free-to-use stock images.

## Files and Structure
- **data**: Contains raw data from Columbia University's MS Journalism program and the U.S. Bureau of Labor Statistics.
- **scraping.py**: Python script used to scrape data from Columbia's program webpages using BeautifulSoup.
- **analysis.ipynb**: Jupyter notebook that includes data cleaning, analysis, and visualizations of the scraped data.
- **visualizations**: Folder containing saved charts and graphs generated during the analysis in ggplot2.
- **README.md**: This file containing project details and instructions.

## Running the Project
### Prerequisites
Ensure you have the following Python libraries installed:
- BeautifulSoup
- Pandas
- Requests
- Matplotlib (for initial visualizations)

For R:
- ggplot2
- Tidyverse
- Datawrapper API

### Steps:
1. Run **scraping.py** to collect data from Columbia's MS Journalism program webpages.
2. Load and clean the data in **analysis.ipynb**.
3. Analyze and visualize the data using **Pandas** for analysis and **ggplot2** in R for data visualization.
4. Optionally, use **Datawrapper** for interactive charts.

## Conclusion
This project sheds light on the financial burden faced by journalism students at Columbia University and compares it with median journalist salaries in the U.S. Through data analysis and visualizations, the project highlights the financial challenges that may arise when pursuing a journalism degree from one of the nation's top institutions.

Feel free to adjust the sections as necessary!
