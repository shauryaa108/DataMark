
# Gapminder Data Explorer 🌍

An interactive data exploration app built using Python and Streamlit to explore global development trends across countries.

## About

As part of my journey into learning Data Science, I wanted to get some hands-on experience instead of just learning concepts theoretically.

I built this application using the Gapminder dataset to experiment with data analysis, explore relationships between different variables, and understand how data visualization can help uncover meaningful insights.

The dataset contains information about 142 countries across 5 continents from 1952 to 2007. I used Python, Pandas, and Plotly to analyze the data and Streamlit to turn the analysis into an interactive web application.

## Live Demo

🌐 **[Try the Application](https://datascienceapp-n8zn82cwzh4kxbaqpwcj7q.streamlit.app/)**

💻 **[GitHub Repository](https://github.com/shauryaa108/DataScienceApp)**

## Features

- Filter data by continent, year, and country.
- View key statistics such as average life expectancy, total population, and median GDP per capita.
- Explore the relationship between GDP per capita and life expectancy through interactive bubble charts.
- Compare country-wise trends in life expectancy, GDP, and population.
- View top countries based on selected metrics.
- Explore filtered datasets and download them as CSV files.

## Dataset

The Gapminder World Development dataset contains:

- 1,704 observations
- 142 countries
- 5 continents
- Data from 1952 to 2007

Some of the key variables include life expectancy, population, GDP per capita, country, continent, and year.

## Tech Stack

- Python
- Pandas & NumPy
- Plotly
- Streamlit
- Jupyter Notebook

## Running Locally

Clone the repository:

```bash
git clone https://github.com/shauryaa108/DataScienceApp.git
cd DataScienceApp
```

Create and activate a virtual environment:

**Windows:**
```powershell
py -m venv .venv
.venv\Scripts\Activate.ps1
```

**Linux / macOS:**
```bash
python3 -m venv .venv
source .venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

The application will open at `http://localhost:8501`.

## What I Explored

While working on this project, I explored:

- Data cleaning and manipulation using Pandas.
- Exploratory Data Analysis (EDA).
- Correlation between economic growth and life expectancy.
- Statistical analysis and identifying trends in datasets.
- Interactive data visualization using Plotly.
- Building and deploying applications using Streamlit.

This was a hands-on project to apply what I've been learning about Data Science and get more comfortable working with real-world datasets.

---

**Built by [Yash Goyal](https://github.com/shauryaa108)**
