# Movie Data Analysis Application

[![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)](https://www.python.org/)
[![PyQt5](https://img.shields.io/badge/PyQt5-5.15.6-green?logo=qt)](https://riverbankcomputing.com/software/pyqt/intro)
[![Pandas](https://img.shields.io/badge/Pandas-1.6.2-yellow?logo=pandas)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.8.2-orange?logo=matplotlib)](https://matplotlib.org/)

---

## Introduction
The **Movie Data Analysis Application** is a PyQt-based GUI tool for exploring and visualising movie datasets. It allows users to:

- Load CSV datasets.
- Display data tables.
- Analyse movie ratings, tags, and trends.
- Generate interactive plots to explore patterns.

This project demonstrates how **Python, PyQt5, Pandas, and Matplotlib** can work together to build a user-friendly data analysis application.

---

## Technologies Used
- **Python 3.10+**
- **PyQt5** – GUI framework for creating responsive interfaces.
- **Pandas** – Data manipulation and analysis.
- **Matplotlib** – Plotting and visualisation library.
- **Jupyter Notebook** – Used for initial dataset exploration.

---

## Dataset
This project uses the **MovieLens 20M Dataset**:

- 20 million ratings
- 465,000 tag applications
- 27,000 movies
- 138,000 users
- 12 million relevance scores across 1,100 tags  

**Dataset link:** [MovieLens 20M](https://grouplens.org/datasets/movielens/20m/)

---

## GUI Overview

### Navigation Panel (Left)
- **Select Dataset** – Load CSV file.
- **View Information** – Display column details.
- **Select Graph Type** – Choose the type of plot.
- **Data Analysis** – Generate visualisations.

### Content Area (Right)
- **Load CSV File & Display Table**
- **View Column Details**
- **Select Graph Type & Configure Axes**
- **Generate & Display Graphs**

### Features
- Table displays first 40 and last 40 rows for large datasets.
- Plots supported: Line, Bar, Scatter, Average Ratings by Year, Top Tags, Rating Frequency.
- Menu bar with `Open`, `Save`, `Exit`.
- Instruction pop-up on launch.

---

## Screenshots

**1. Home Screen / Dataset Load**
![Home Screen](screenshots/home_screen.png)

**2. Column Info Display**
![Column Info](screenshots/column_info.png)

**3. Graph Selection**
![Graph Selection](screenshots/graph_selection.png)

**4. Generated Plot**
![Generated Plot](screenshots/generated_plot.png)

---

## Example Workflow
1. Load `ratings.csv` or `tags.csv`.
2. View column information.
3. Select a graph type and X/Y axes.
4. Click **Generate Plot** to visualise data.
5. Save plots or export results as needed.

---

