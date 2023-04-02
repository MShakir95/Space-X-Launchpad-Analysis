# SpaceX Falcon9 Flight Data Analysis

The SpaceX Falcon9 Flight Data Analysis project is a data analysis project written in Python and performed in Jupyter Notebooks. The project uses data from SpaceX's Falcon9 flights to predict future flight success and discover what variables affect flight success. The data used for the analysis was obtained from SpaceX's API and Wikipedia entry.

## Installation

To use the SpaceX Falcon9 Flight Data Analysis project, follow these steps:

Clone this repository: git clone https://github.com/ShakirMA/Space-X-Launchpad-Analysis.git
Navigate to the project directory: cd Spacex-X-Launchpad-Analysis
Install the required dependencies: pip install -r requirements.txt
Launch the Jupyter Notebooks: jupyter notebook

## Usage

The project consists of several Jupyter Notebooks that perform different aspects of the data analysis. The notebooks are organized in the following manner:

01_data_collection API.ipynb - collects data from SpaceX's API and stores it in a SQL database (IBM's db2).
02_data_collection_Webscrapping.ipynb - collects data from SpaceX's Wikipedia entry and stores it in a SQL database (IBM's db2)
03_data_wrangling.ipynb - cleans and preprocesses the collected data.
04_SQL_EDA.ipynb - performs exploratory data analysis SQL queries
05_Exploratory_Data_Analysis_Visualization.ipynb - performs the data analysis, including exploratory data analysis and hypothesis testing
06_ML_Modelling.ipynb - performs predictive modeling.
07_Dashboard_folium.ipynb - creates visualizations to help communicate the results of the data analysis using an interactive dashboard.

To use the notebooks, launch Jupyter Notebook and navigate to the project directory. Click on the desired notebook to open it and follow the instructions provided within the notebook.

The combined results were presented in a pdf file: SPACEX_LAUNCHPAD_ANALYSIS.pdf

## Data Sources

The data used in this project was obtained from the following sources:

SpaceX API - https://api.spacexdata.com/v4/rockets/
SpaceX Wikipedia entry - https://en.wikipedia.org/wiki/List_of_Falcon_9_and_Falcon_Heavy_launches?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMDS0321ENSkillsNetwork26802033-2022-01-01

## Dependencies

The SpaceX Falcon9 Flight Data Analysis project requires the following dependencies:

pandas
numpy
matplotlib
dash
folium
sklearn
requests
beautifulsoup4

These dependencies are listed in the requirements.txt file and will be installed when you run pip install -r requirements.txt.

## License

The SpaceX Falcon9 Flight Data Analysis project is licensed under the MIT license. See the LICENSE file for more information.
