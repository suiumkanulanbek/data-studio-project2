# Journalism School Cost Analysis

This project analyzes the cost of journalism school compared to other educational programs, using data from the U.S. Bureau of Labor Statistics.

## Project Overview

This data analysis project aims to investigate whether journalism school is expensive relative to other educational programs. The study combines web scraping, data analysis, and visualization techniques to provide insights into the costs associated with journalism education.

## Methodology

1. **Data Collection**: Used Beautiful Soup to scrape relevant data from the U.S. Bureau of Labor Statistics website[1].
2. **Data Analysis**: Employed pandas in Python to clean, process, and analyze the scraped data[2].
3. **Visualization**: Created visualizations using both R's tidyverse and Datawrapper to illustrate the findings[3].

## Key Findings

- Journalism degrees tend to cost more than law and engineering degrees[4].
- [Include 2-3 other key findings from your analysis]

## Repository Structure

```
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
│   ├── 01_web_scraping.ipynb
│   ├── 02_data_analysis.ipynb
│   └── 03_visualization.ipynb
├── R/
│   └── visualization_scripts.R
├── visualizations/
├── README.md
└── requirements.txt
```

## Setup and Installation

1. Clone this repository
2. Install required Python packages: `pip install -r requirements.txt`
3. Install required R packages: `install.packages(c("tidyverse", "ggplot2"))`

## Usage

1. Run the Jupyter notebooks in the `notebooks/` directory sequentially
2. Execute R scripts in the `R/` directory for additional visualizations

## Future Work

- Expand the analysis to include more educational programs
- Investigate the return on investment for journalism degrees
- [Add any other potential future directions for the project]

## License

This project is licensed under the MIT License.

Citations:
[1] https://medium.datadriveninvestor.com/how-to-write-a-good-readme-for-your-data-science-project-on-github-ebb023d4a50e
[2] https://www.youtube.com/watch?v=0N9xekdKCwk
[3] https://book.the-turing-way.org/project-design/project-repo/project-repo-advanced.html
[4] https://github.com/JIC-CSB/data-analysis-project
[5] https://gist.github.com/ericmjl/27e50331f24db3e8f957d1fe7bbbe510
[6] https://github.com/ahgroup/data-analysis-template
[7] https://github.com/sfbrigade/data-science-wg/blob/master/dswg_project_resources/Project-README-template.md
[8] https://github.com/elizabethdaly/data-analysis-project/blob/master/README.md
