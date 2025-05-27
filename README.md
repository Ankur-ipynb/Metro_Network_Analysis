Delhi Metro Network Analysis
Overview
This project analyzes the Delhi Metro Network using a dataset containing station details such as names, lines, coordinates, opening dates, and layouts. It provides interactive visualizations using Folium for mapping and Plotly for statistical insights, including station distribution, line analysis, and layout trends. The project is implemented in Python and designed to be run in a Jupyter Notebook environment.
Features

Interactive Map: Visualize metro stations on a Folium map with color-coded lines and tooltips.
Temporal Analysis: Bar chart of stations opened per year.
Line Analysis: Comparison of station counts and average distances between stations per metro line.
Layout Distribution: Visualization of station layout types (e.g., Elevated, Underground).
Dependencies: Uses pandas, folium, plotly for data processing and visualization.

Prerequisites

Hardware: Windows PC with 8GB RAM, 100GB free storage.
Software:
Python 3.9+
Jupyter Notebook


Libraries:
pandas
folium
plotly


Dataset: Delhi-Metro-Network.csv (place in project directory, e.g., D:\Metro_Analysis\).

Installation

Create and activate a virtual environment:D:\>python -m venv D:\metro_venv
D:\>D:\metro_venv\Scripts\activate
(metro_venv) D:\>


Install dependencies:(metro_venv) D:\>pip install pandas folium plotly jupyter


Download the dataset (Delhi-Metro-Network.csv) and place it in D:\Metro_Analysis\.
Start Jupyter Notebook:(metro_venv) D:\>jupyter notebook



Usage

Open metro_analysis.ipynb in Jupyter Notebook.
Run all cells to:
Load and preprocess the dataset.
Generate an interactive Folium map.
Create Plotly visualizations for station openings, line analysis, and layout distribution.


View outputs:
Map: Displayed in the notebook.
Plots: Interactive bar charts for analysis.
Console: Data summaries and verification steps.



Project Structure

README.md: Project overview and setup instructions.
LICENSE: MIT License for the project.
metro_analysis.ipynb: Main notebook with analysis code.
Delhi-Metro-Network.csv: Dataset (sample added).
docs/project_documentation.md: Detailed project documentation.

Contributing
Contributions are welcome! Please fork the repository, create a feature branch, and submit a pull request with your changes. Ensure code follows PEP 8 guidelines and includes comments for clarity.
License
This project is licensed under the MIT License. See the LICENSE file for details.
