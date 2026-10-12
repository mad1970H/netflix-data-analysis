# Netflix Content Analysis | Python & Power BI

## Project Overview

This project explores Netflix Movies and TV Shows data using Python, Pandas, Matplotlib, and Microsoft Power BI.

The project combines data cleaning and exploratory data analysis in Python with a two-page Power BI dashboard to investigate Netflix's content library, discover patterns, and communicate key findings through interactive visualizations.

## Project Objectives

- Analyze the distribution of Movies and TV Shows.
- Explore Netflix content additions over time.
- Identify the countries contributing the most titles.
- Analyze popular genres and their trends over time.
- Investigate movie duration patterns.
- Compare content ratings across Movies and TV Shows.
- Explore directors represented in the dataset.

## Tools & Technologies

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- Microsoft Power BI

## Repository Structure

```text
netflix-data-analysis/
│
├── data/
│   └── netflix_titles.csv
│
├── notebooks/
│   └── netflix_analysis.ipynb
│
├── powerbi/
│   └── netflix_dashboard.pbix
│
├── images/
│   ├── dashboard_page1.png
│   └── dashboard_page2.png
│
├── requirements.txt
└── README.md
```

## Dataset

This project uses the Netflix Movies and TV Shows dataset, which contains information about titles available on Netflix, including their type, release year, date added, country, genre, rating, duration, and director.

**Dataset source:** [Netflix Movies and TV Shows — Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)

## Python Data Analysis

The Jupyter Notebook uses Python and Pandas to explore and prepare the dataset.

The analysis includes:

- Inspecting the dataset and data types.
- Identifying missing values.
- Cleaning and transforming columns.
- Processing date and duration information.
- Comparing Movies and TV Shows.
- Analyzing content by country, genre, rating, and year.
- Creating visualizations with Matplotlib.

## Power BI Dashboard

The Power BI report contains two pages designed to explore Netflix content from different perspectives.

### Page 1 — Netflix Content Overview

This page provides a high-level overview of Netflix's content library.

**Key visualizations:**
- KPI cards for Total Titles, Movies, and TV Shows.
- Netflix content added over time.
- Movies vs. TV Shows distribution.
- US vs. International content.
- Top 10 Netflix genres.
- Top countries by number of titles.

**Dashboard Preview**

![Netflix Content Overview](images/dashboard_page1.png)

### Page 2 — Detailed Content Analysis

This page focuses on movie duration, genre trends, ratings, and directors.

**Key visualizations:**
- Average movie duration over time.
- Popular genres over time.
- Average movie duration KPI.
- Rating distribution for Movies vs. TV Shows.
- Top 10 directors on Netflix.
- Interactive filters for content type and origin.

**Dashboard Preview**

![Netflix Detailed Analysis](images/dashboard_page2.png)

## Key Findings

Based on the dashboard:

1. **Movies dominate the dataset.** The dashboard reports 5,558 Movies and 189 TV Shows, out of 5,747 titles in total. Movies account for approximately 96.7% of the displayed titles.

2. **Content additions peaked around 2019.** The content-over-time chart shows a substantial increase beginning around 2016, with the highest point around 2019, followed by a decline.

3. **The United States leads by title count.** The country chart shows the United States as the largest contributor, followed by India and the United Kingdom.

4. **The average movie duration is approximately 101 minutes.** The dashboard's average-duration KPI displays 101.18 minutes.

## Key Questions Explored

- Are Movies more common than TV Shows in the dataset?
- How has the number of titles added to Netflix changed over time?
- Which countries have the most titles?
- Which genres appear most frequently?
- How does average movie duration vary by release year?
- Which content ratings are most common for Movies and TV Shows?
- Which directors have the most titles in the dataset?

## How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/netflix-data-analysis.git
cd netflix-data-analysis
```

Replace `YOUR-USERNAME` with your GitHub username.

### 2. Install Python Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Jupyter Notebook

```bash
jupyter notebook
```

Open `notebooks/netflix_analysis.ipynb` and run the cells.

Make sure the dataset is available in the expected location and update the file path in the notebook if necessary.

### 4. Open the Power BI Dashboard

Open `powerbi/netflix_dashboard.pbix` using Power BI Desktop.

If required, update the dataset source path and refresh the data.

## Skills Demonstrated

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Data Manipulation with Pandas
- Data Visualization with Matplotlib
- Data Interpretation
- Power BI Dashboard Design
- KPI Development
- Interactive Data Exploration
- Business Intelligence Reporting

## Future Improvements

- Add more detailed findings and business recommendations.
- Improve dashboard interactivity and filtering.
- Explore trends in content ratings and country-level distributions.
- Extend the analysis using SQL.
- Publish an accessible online dashboard, where appropriate.

## Author

**Netflix Content Analysis — Data Analytics Portfolio Project**

Developed as a practical project to demonstrate data analysis and visualization skills using Python and Power BI.
