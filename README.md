# Netflix Data Analysis

Analyze and visualize Netflix’s global content catalog to uncover trends in content type, genre, country of production, and movie durations.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Data Source](#data-source)
- [Setup & Installation](#setup--installation)
- [Usage](#usage)
- [Methodology](#methodology)
- [Visualizations](#visualizations)
- [Key Insights](#key-insights)
- [Credits](#credits)
- [License](#license)

---

## Project Overview

This project explores and visualizes Netflix’s content library using Python, pandas, matplotlib, and seaborn. It provides insights into how Netflix’s catalog has evolved over time, which countries and genres dominate, and how movie durations are distributed.

---

## Features

- **Data Cleaning:** Handles missing values and standardizes columns for analysis.
- **Content Type Analysis:** Compares Movies vs TV Shows.
- **Temporal Trends:** Shows how content addition has changed over the years.
- **Country Analysis:** Identifies top content-producing countries.
- **Genre Analysis:** Highlights the most popular genres.
- **Duration Analysis:** Examines the distribution of movie durations.
- **Beautiful Visualizations:** All plots are saved to the `images/` directory.

---

## Project Structure

netflix-data-analysis/
│
├── data/
│   ├── raw/
│   │   └── netflix_titles.csv           # Original raw dataset
│   ├── cleaned/
│   │   └── netflix_cleaned.csv          # Cleaned dataset after handling missing values, etc.
│   └── processed/
│       └── netflix_processed.csv        # Final processed dataset used for analysis
│
├── images/
│   └── (generated plots)
│
├── notebooks/
│   └── data-visualization.ipynb         # Main analysis and visualization notebook
│
├── report.md                            # Project report
└── README.md                            # Project documentation

---

## Data Source

- The dataset used is a processed version of Netflix’s public catalog data.
- File: `data/processed/netflix_processed.csv`

---

## Setup & Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/netflix-data-analysis.git
   cd netflix-data-analysis
   ```

2. **Install dependencies:**
   ```bash
   pip install pandas matplotlib seaborn
   ```

3. **(Optional) Start Jupyter Notebook:**
   ```bash
   jupyter notebook notebooks/data-visualization.ipynb
   ```

---

## Usage

- **Run the notebook:**  
  Open `notebooks/data-visualization.ipynb` in Jupyter and run all cells to reproduce the analysis and generate plots.
- **View results:**  
  All generated plots are saved in the `images/` directory.
- **Read the report:**  
  See `report.md` for a summary of findings and insights.

---

## Methodology

1. **Data Cleaning:**
   - Replaced missing values in `director`, `cast`, and `country` with `'Unknown'`.
   - Converted `date_added` to datetime.
   - Extracted numeric values from `duration` for movies.

2. **Analysis:**
   - Counted and visualized Movies vs TV Shows.
   - Analyzed content addition trends by year.
   - Identified top countries and genres.
   - Explored movie duration statistics.

3. **Visualization:**
   - Used matplotlib and seaborn for all plots.
   - Ensured clear, non-overlapping labels and legends.

---

## Visualizations

- **Content Type Distribution:** Bar plot of Movies vs TV Shows.
- **Content Type Proportion:** Pie chart with percentages and a legend.
- **Content Added Over Time:** Line plot by year and type.
- **Top Countries:** Bar plot of the top 10 content-producing countries.
- **Top Genres:** Bar plot of the top 10 genres.
- **Movie Duration:** Histogram and boxplot of movie durations.

All plots are saved in the `images/` directory for easy access.

---

## Key Insights

- Movies are more prevalent than TV Shows in the dataset.
- The number of titles added to Netflix has increased over time, with some fluctuations.
- The United States and India are among the top content-producing countries.
- Drama, Comedy, and Documentary are the most common genres.
- Most movies are between 80 and 120 minutes long.

---

## Credits

- **Developed by:** Anup S Bhandarkar 
- **Dataset:** Netflix public catalog (processed version)
- **Tools:** Python, pandas, matplotlib, seaborn

---

## License

This project is licensed under the MIT License.

---
