# spotify_eda_amydaniel

Exploratory Data Analysis (EDA) with Spotify Streaming Data

This repository contains a follow-along Exploratory Data Analysis project using a Spotify tracks dataset. The work in this project was completed by following an instructional walkthrough video step by step as part of a Code:You data analysis lesson.

The goal of this project is to practice basic EDA techniques, including inspecting data, summarizing variables, and visualizing relationships using pandas, Matplotlib, and seaborn.

---

## Project Purpose

Exploratory Data Analysis (EDA) is the process of getting familiar with a dataset before doing deeper analysis or modeling. In this project, EDA was used to:

- Understand the structure of the Spotify dataset  
- Identify missing or unexpected values  
- Explore distributions of numeric variables  
- Visualize relationships between features  

This project focuses on exploration rather than drawing conclusions or building models.

---

## Project Structure

spotify_eda_amydaniel/
│
├── data/
│ ├── Spotify_2024_Global_Streaming_Data.csv
│ └── Cleaned_Spotify_2024_Global_Streaming_Data.csv
│
├── notebooks/
│ └── spotify_plots_walkthrough.ipynb
│
├── plots/
│ ├── average_streams_barplot.png
│ ├── average_streams_by_artist_barplot.png
│ ├── halfsies_pie_chart.png
│ ├── pearson_heatmap.png
│ └── scatter_pop_plot.png
│
└── README.md


---

## How to Run This Project

### 1. Install Required Libraries

Make sure the following libraries are installed:

pip install pandas matplotlib seaborn

### 2. Open the Notebook

Open the Jupyter notebook located at:

notebooks/spotify_plots_walkthrough.ipynb

You can open this file using Jupyter Notebook or VS Code.

### 3. Run the Notebook

Run the cells in order to reproduce the exploratory analysis and visualizations shown in the lesson walkthrough. The generated plots are saved to the `plots/` folder.

---

## Description of Work

The notebook follows the tutorial step by step and includes:

- Loading and inspecting the Spotify dataset  
- Checking column types and summary statistics  
- Creating bar plots, scatter plots, pie charts, and a correlation heatmap  
- Saving visualizations as image files  

No additional analysis beyond the walkthrough was added.

---

## Notes

This project was completed as a learning exercise for Exploratory Data Analysis. The emphasis was on practicing EDA techniques and becoming comfortable with exploring a new dataset using pandas and visualization libraries.

---

## Course Context

This repository was created for a Code:You lesson on Exploratory Data Analysis and Git-based project organization.
