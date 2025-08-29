# COVID-19-VISUALIZER
🦠 COVID-19 Data Visualizer
📌 Overview

The COVID-19 Data Visualizer is an interactive project built using Python and Jupyter Notebook that analyzes and visualizes the spread of COVID-19 globally. It uses the Johns Hopkins University CSSE COVID-19 dataset (time-series data) and provides insights into confirmed cases, recoveries, and deaths across countries and over time.

This project is designed to help users:

Track the growth of COVID-19 cases globally.

Visualize data trends with graphs and charts.

Understand the impact of the pandemic across regions.

📊 Features

✔️ Load live COVID-19 data from an online CSV dataset.
✔️ Clean and transform raw data into a usable format.
✔️ Generate interactive graphs (line plots, bar charts, heatmaps).
✔️ Compare countries to see which regions were most affected.
✔️ Present the information in an easy-to-understand dashboard style.

🗂️ Dataset

The dataset comes from:
Johns Hopkins University CSSE COVID-19 GitHub Repository

time_series_covid19_confirmed_global.csv

⚙️ Requirements

To run the project, install the following dependencies:

pip install pandas numpy matplotlib seaborn plotly


(Optional: streamlit can be used if you want to deploy it as a web app)

🚀 How to Run

Clone the repository:

git clone https://github.com/your-username/covid19-visualizer.git
cd covid19-visualizer


Open the Jupyter Notebook:

jupyter notebook covid_visualizer.ipynb


Run the cells step by step to:

Load the dataset

Clean and process the data

Generate visualizations

📈 Example Visualizations

Global confirmed cases over time

Top 10 countries affected

Country-wise comparison graphs

Heatmaps showing intensity of cases

🎯 Future Enhancements

Build a Streamlit dashboard for live interactivity.

Add real-time updates from APIs.

Create Power BI or Tableau dashboards for advanced visualization.

🙌 Acknowledgments

Johns Hopkins University CSSE for maintaining the dataset.

Python open-source libraries (Pandas, Matplotlib, Seaborn, Plotly)
